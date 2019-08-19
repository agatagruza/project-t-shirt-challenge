# This is the repo for #sg_project-t-shirt challenge :shirt:


<img height="32" width="32" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/simpleicons.svg" /> <ins> OVERVIEW</ins></br>
**Project T-Shirt** is a design competition initiative created by fellow scholars of [Secure and Private AI Challenge](https://www.udacity.com/facebook-AI-scholarship) under the sponsorship of Udacity and Facebook. The main goal of Project T-shirt is:
1.	To offer students with varying levels of AI experience an opportunity to complete a project.
2.	To create a souvenir of the experience. Top three voted images will be featured on a popular swags such as t-shirts, mugs, hoodies, stickers and more. Later on  everyone will be able to purchase those merchants from official https://teespring.com/ website. It’s a great initiative as all proceeds go to charity. </br></br>
Our team UNSTOPPABLE including [@agatagruza](https://github.com/agatagruza), [@amalphonse](https://github.com/amalphonse) and [@esridhar126](https://github.com/esridhar126) won the challenge.   :star2::star2::star2:


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

### **Contributors:**
***
:cyclone: **Agata Gruza** 
- GitHub: [@agatagruza](https://github.com/agatagruza) 
- Linkedin: [@agatagruza](https://www.linkedin.com/in/agatagruza/)</br>

:cyclone: **Anju Mercian** 
- GitHub: [@amalphonse](https://github.com/amalphonse)
- Linkedin: [@amalphonse](https://www.linkedin.com/in/anjumercian/)
