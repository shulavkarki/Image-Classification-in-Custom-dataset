# Image-Classification-in-Custom-dataset-with-Pytorch
This repo is about building image classifier in custom datasets.  
Here, i've used MNIST digit dataset. 
Dataset looks something like this.  
<!-- ![image](https://user-images.githubusercontent.com/40908371/175806103-01d7d07e-54aa-4e44-9adf-5cf9233e00de.png) -->
<img src="https://user-images.githubusercontent.com/40908371/175806103-01d7d07e-54aa-4e44-9adf-5cf9233e00de.png" alt="drawing" width="350"/>


Results:  

|  Optimizer | Epoch | Learning Rate| Training Accuracy | Testing Accuracy |
| --- | --- | --- | --- | --- |
|     SGD Gradient Descent          |  10  | 0.001 | 94.06% | 94.09%  


---------------------------------------------------------------------------------  

Note: One can easily train model in any given custom dataset(considering above datafolder structure.)  
The dataset used is MNIST DIGIT. And the model is quite simple. 
If you're to apply in high resolution dataset, you've to make the model deep. 
And do the hyperparameter tuning. 
