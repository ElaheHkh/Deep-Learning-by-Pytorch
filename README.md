# Deep Learning by Pytorch Part 1 Gradient Descent
Tutorial of Machine Learning and Deep Learning by Pytorch
## Train the Model Steps
### 1- Generate Predictions
### 2- Calculate the loss
### 3- Compute Gradients w.r.t the weights and biases
### 4- Adjust the weights by subtraqcting a smaqll quantity proportional to the gradient
### 5- Reset the gradients to zero


## Create tensors:
- x = torch.tensor(3.) --> tensor(3.) -->  y is Undifferentiable based on x
- w = torch.tensor(4., requires_grad=True) --> tensor(4., requires_grad=True) --> y is Differentiable based on w 
- b = torch.tensor(5., requires_grad=True) --> tensor(5., requires_grad=True) --> y is Differentiable based on b 

## Arithmetic operations
 
-  y = w * x + b

## Compute derivatives
 
- y.backward()

## Display gradients

- print('dy/dx:', x.grad) --> dy/dx: None
- print('dy/dw:', w.grad) --> dy/dw: tensor(3.)
- print('dy/db:', b.grad) --> dy/db: tensor(1.)






