# Textline-Segmentation-using-UNet.

Recognizing full pages requires the page to be split into lines as most of the text recognition model
works on line level.Here I have used U-Net to do semantic segmentation of the text lines and predict 
the mask associated with them.Contour detection can be applied on these mask to split the page into 
lines.I have used my own privated dataset which I created by manual annotation.

# Requirements
### Keras with tensorflow
### Opencv
### Numpy

