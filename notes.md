# 对抗训练
    1. 鞍点公式（最小最大值公式）
    
   $$\min_{\theta} \left(E_{(x,y)\sim D} \left[\max_{\Vert\delta\Vert \leq \epsilon } J(\theta,x+\delta,y) \right] \right)$$
    
    在实际优化求解的时候，内部对应着对抗攻击生成对抗样本的过程，
    所以对抗训练实际上是在由干净样本生成的对抗样本上进行训练。
    所以通常对抗攻击越强，对抗训练的效果也越好。
    也就是说要求模型在worst-case 输入情况下依然鲁棒，模型才有可能得到最优的鲁棒性。
  
   \begin{equation}\n
   \begin{split}\n
   \mbox{Repeat:} \\\\\n
   \quad \\mbox{1. Select minibatch $B$, initialize gradient vector $g := 0$} \\\\\n
   "& \\quad \\mbox{2. For each $(x,y)$ in $B$:} \\\\\n",
   "& \\quad \\quad \\mbox{a. Find an attack perturbation $\\delta^\\star$ by (approximately) optimizing } \\\\\n",
   "& \\qquad \\qquad \\qquad \\delta^\\star = \\argmax_{\\|\\delta\\| \\leq \\epsilon} \\ell(h_\\theta(x + \\delta), y) \\\\\n",
   "& \\quad \\quad \\mbox{b. Add gradient at $\\delta^\\star$} \\\\\n",
   "& \\qquad \\qquad \\qquad g:= g + \\nabla_\\theta \\ell(h_\\theta(x + \\delta^\\star), y) \\\\\n",
   "& \\quad \\mbox{3. Update parameters $\\theta$} \\\\\n",
   "& \\qquad \\qquad \\qquad \\theta:= \\theta - \\frac{\\alpha}{|B|} g\n",
   "\\end{split}\n",
   "\\end{equation}\n",
 
  

  
  

