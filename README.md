# GradCAM-visualizations---Explainable-AI
GradCAM visualizations for elephant images

The project demonstrates the use of the popular GradCAM (Gradient-weighted Class Activation Mapping) technique to generate visualizations that highlight the most important regions in elephant images that contribute to the classification decision of a deep neural network. 

## Implementation
The implementation uses a pre-trained VGG model, which has been trained on ImageNet dataset, including elephant images. The GradCAM algorithm is applied to the last convolutional layer of the model to generate a heatmap that visualizes the regions of the elephant image that the model is focusing on to make its prediction. The project includes a Jupyter Notebook that walks through the steps to implement GradCAM visualizations on elephant images and allows for further experimentation and customization. The project's code and data are freely available for use and modification, making it a valuable resource for researchers, developers, and anyone interested in understanding the inner workings of deep neural networks.

## Credits
The original implementation of GradCAM in PyTorch, which served as a reference for my implementation on elephants, can be credited to Stepan Ulyanin, whose article on Medium titled "Implementing Grad-CAM in PyTorch https://medium.com/@stepanulyanin/implementing-grad-cam-in-pytorch-ea0937c31e82" provided a detailed explanation of the technique and its implementation.
