# Deep-Learning-by-Pytorch
Tutorial of Machine Learning, Deep Learning by Pytorch

Part 1 ==> Gradient Descent

## Create tensors:
- x = torch.tensor(3.) ==> tensor(3.) ==> make y Undifferentiable based on x
- w = torch.tensor(4., requires_grad=True) ==> tensor(4., requires_grad=True) ==> making y Differentiable based on w 
- b = torch.tensor(5., requires_grad=True) ==> tensor(5., requires_grad=True) ==> making y Differentiable based on b 

## Arithmetic operations
 
-  y = w * x + b

##Compute derivatives
 
- y.backward()

## Display gradients

- print('dy/dx:', x.grad) ==> dy/dx: None
- print('dy/dw:', w.grad) ==> dy/dw: tensor(3.)
- print('dy/db:', b.grad) ==> dy/db: tensor(1.)






