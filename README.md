# Dashtoon-Assignment
# Working
The style transfer works by defining two types of losses viz. style loss (for the style portion of the image) and content loss(for content portion of image). The two losses measure the distance of the respective parameters from their source images and the objective of the algorithm is to minimize both so that the final output image can have the content form the content image and the style from the style image.

# Steps
Loads the VGG-19 model pre-trained on a large dataset of ImageNet
Computes the Content cost
Computes the Gram matrix which is later used to find the Style cost
Computes the Style cost from several layers
Initialises the generated image as a Content Image
Outputs the generated image in folder-output
