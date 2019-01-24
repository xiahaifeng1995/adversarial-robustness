# 对抗训练

## 优化公式
  $$
  \mathop{\min}_\theta (\E_(x,y)\sim\D)[\mathop{\max_\delta\in\S} \J(\theta, x+\delta, y))]
    
