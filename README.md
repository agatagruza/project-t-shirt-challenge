# This is the repo for #sg_project-t-shirt challenge :shirt:


<img height="32" width="32" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/simpleicons.svg" /> <ins> OVERVIEW</ins></br>
**Project T-Shirt** is a design competition initiative created by fellow scholars of [Secure and Private AI Challenge](https://www.udacity.com/facebook-AI-scholarship) under the sponsorship of Udacity and Facebook. The main goal of Project T-shirt is:
1.	To offer students with varying levels of AI experience an opportunity to complete a project.
2.	To create a souvenir of the experience. Top three voted images will be featured on a popular swags such as t-shirts, mugs, hoodies, stickers and more. Later on  everyone will be able to purchase those merchants from official [TeeSpring website](https://teespring.com/ ). It’s a great initiative as all proceeds go to charity. </br></br>

The bar was high and all participants worked very hard to create high quality images. Each picture was special and told unique story. Total of :three: :three: :eight: images were submitted. Our team UNSTOPPABLE including [@agatagruza](https://github.com/agatagruza), [@amalphonse](https://github.com/amalphonse) and [@esridhar126](https://github.com/esridhar126) uploaded :eight: :seven: pictures and at the end won the challenge  :star2::star2::star2: </br></br>

:shirt: WINNING PICTURE: :shirt:
![WINNER](https://user-images.githubusercontent.com/7014697/63242448-42f10a80-c20c-11e9-9ab5-ab856cdb8f3c.jpg)</br>


<img height="32" width="32" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/simpleicons.svg" /> <ins> HOW</ins></br>
Generate an image using a ML/AI method. 

<img height="32" width="32" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/simpleicons.svg" /> <ins> DATA</ins></br>
<img height="32" width="32" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/simpleicons.svg" /> <ins> INSTALATION</ins></br>
<img height="32" width="32" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/simpleicons.svg" /> <ins> USAGE</ins></br>

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

<img height="32" width="32" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/simpleicons.svg" /> <ins> RESOURCES</ins></br>
:link: https://trello.com/b/ljgxuVOu/gan-t-shirt-contest </br>
:link: https://www.youtube.com/watch?v=8_vhbNpyIk4&feature=youtu.be </br>
:link: https://github.com/ProGamerGov/Torch-Models </br>

### **Contributors:**
***
:cyclone: **Agata Gruza** 
- GitHub: [@agatagruza](https://github.com/agatagruza) 
- Linkedin: [@agatagruza](https://www.linkedin.com/in/agatagruza/)</br>

:cyclone: **Anju Mercian** 
- GitHub: [@amalphonse](https://github.com/amalphonse)
- Linkedin: [@amalphonse](https://www.linkedin.com/in/anjumercian/)

Link to slide show
