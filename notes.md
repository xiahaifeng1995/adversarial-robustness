# 对抗训练
    1. 鞍点公式（最小最大值公式）
    
   $$\min_{\theta} \left(E_{(x,y)\sim D} \left[\max_{\Vert\delta\Vert \leq \epsilon } J(\theta,x+\delta,y) \right] \right)$$
    
    在实际优化求解的时候，最小最大值的优化顺序很重要。内部最大值问题对应着对抗攻击生成对抗样本的过程,
    固定好内部的最大值，再来求解外部的最小值问题。
    所以对抗训练实际上是相当于在由干净样本生成的对抗样本上进行训练。
    所以通常对抗攻击越强，对抗训练的效果也越好。
    也就是说要求模型在worst-case 输入情况下依然鲁棒，模型才有可能得到最优的鲁棒性。
  > Repeat:<br>
     &nbsp; 1. Selet minibatch B, initialize gradient vecter $ g :=0 $<br>
     &nbsp; 2. For each $ (x,y) $ in B: <br>
       &nbsp; &nbsp;    a. Find an attack perturbation $ \delta^* $ by (approxiamtely) optimizing <br>  
       &nbsp; &nbsp;&nbsp; &nbsp;   $ \delta^* = \mathop{\arg\max}_{\Vert\delta\Vert \leq \epsilon } J(\theta,x+\delta,y) $$ <br>
       &nbsp; &nbsp;    b. Add gradient at $ \delta^* $ <br>
       &nbsp; &nbsp;&nbsp; &nbsp;   $ g :=  g + \bigtriangledown_{\theta} J(\theta,x+\delta^*,y) $ <br>
       
       
      
   
  

  
  

