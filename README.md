# NeuralStyleTransfer
This is my tensorflow implementation for the paper, A Neural Algorithm of Artistic Style. I use Adam optimizer instead of L-BFGS to save some implementation times.

# Built With
Python Packages : tensorflow 2, numpy, PILLOW, and with kera's pretrained VGG19 

<!-- GETTING STARTED -->
# Getting Started
Execute the notebook in Google Colab
Set up the paths for content image and style images
Decide the parameters
- the intimidate output layers for style models 
- the layer weight for style outputs
- the weights for content and style during trainings. 
- training parameters


<!-- CONTACT -->
## Contact
Brandon Chen - zxarda@gmail.com



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
Pictures and Gram Matrix implementation is from Google's Tutorials
https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/generative/style_transfer.ipynb#scrollTo=GM6VEGrGLh62
https://colab.research.google.com/github/tensorflow/models/blob/master/research/nst_blogpost/4_Neural_Style_Transfer_with_Eager_Execution.ipynb#scrollTo=ES9dC6ZyJBD2

Training Structure is adepted from below link
https://www.geeksforgeeks.org/neural-style-transfer-with-tensorflow/
