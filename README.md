# This is the repo for #sg_project-t-shirt challenge


<img height="32" width="32" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/simpleicons.svg" /> <ins>OVERVIEW</ins></br>
Project T-Shirt was an initiative created by fellow scholars of Secure and Provate AI Challenge organized by Udacity and Facebook.
The goal of *Project T-shirt* was two-folded:
1. To offer students with varying levels of AI experience an opportunity to complete a project.
2. To create a souvenir of the experience.

This project uses Neural style transfer with Open CV.

Neural style transfer is an optimization technique used to take two images, a content image and a style image and blend them together and produce a "painted" like image as output.

Neural style transfer uses three types of loss to merge the images
content loss, style loss and total variation loss. The image is first trained to reproduce the style and then the network is trained to apply the image content. Training the model uses instance normalization than bathch normalization for faster real time performance and also for aesthetically pleasing images.

We chose this model for our project because this gave faster results and required less epochs to train.
How the code is implemented:
1) Uses uploads two image one for content and another for style
2)Then we take the style from one image using style loss calculation
3) take the content from the content image using content loss 
4) Merge the style with the content.

The original neural style transfer algorithm was introduced by Gatys et al. in their 2015 paper, A Neural Algorithm of Artistic Style (in fact, this is the exact algorithm that I teach you how to implement and train from scratch inside Deep Learning for Computer Vision with Python).

Follow tutorial by</br>
:link: https://www.pyimagesearch.com/2018/08/27/neural-style-transfer-with-opencv/ </br>
:link: https://github.com/ProGamerGov/Torch-Models
