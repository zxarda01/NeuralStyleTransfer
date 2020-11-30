## NeuralStyleTransfer
This is my tensorflow implementation for the paper, [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576). I use Adam optimizer instead of L-BFGS to save some implementation times. 

## Requirements
Python 3.7
Packages : tensorflow 2, numpy, PILLOW, 
Data : Kera's pretrained VGG19 

<!-- GETTING STARTED -->
## Getting Started
Execute the notebook in Google Colab
Set up the paths for content image and style images
Decide the parameters
- the intimidate output layers for style models 
- the layer weight for style outputs
- the weights for content and style during trainings. 
- training parameters

## Examples 
Combine a yellow labrador picture and Wassily Kandinsky's Composition 7

![Test Image 1](https://github.com/zxarda01/NeuralStyleTransfer/blob/main/Examples/Example1.png)

This result is from a street view and Vincent's Stary Night

![Test Image 2](https://github.com/zxarda01/NeuralStyleTransfer/blob/main/Examples/Example2.png)

<!-- CONTACT -->
## Contact
Brandon Chen - zxarda@gmail.com

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
[A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)

Pictures and Gram Matrix implementation is from [Google's tutorial](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/generative/style_transfer.ipynb#scrollTo=GM6VEGrGLh62) and [Another Google tutorial](https://colab.research.google.com/github/tensorflow/models/blob/master/research/nst_blogpost/4_Neural_Style_Transfer_with_Eager_Execution.ipynb#scrollTo=ES9dC6ZyJBD2)

Training Structure is adepted from [Geeksforgeeks's turorial](https://www.geeksforgeeks.org/neural-style-transfer-with-tensorflow/)
