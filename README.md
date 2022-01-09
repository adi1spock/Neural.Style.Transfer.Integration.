## Table of content
* [Intro](#intro)
* [Neural Style Transfer](#neural-style-transfer)
* [Working Example](#working-example)
## Intro
I have added a desktop GUI using python tkinter module on top of the neural style transfer developed using tensorflow by [@jcjhonson](https://github.com/jcjohnson/fast-neural-style.git).You can easily select the image of which style transfer you want to do on video feed taken by your desktop web cam.
## Neural Style Transfer
Neural style transfer is an optimization technique used to take two images—a content image and a style reference image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network.[You can learn more about it here.](https://www.tensorflow.org/tutorials/generative/style_transfer)
## Working Example
![gui](./Screenshot (4330).png)
![web cam style transfer](./Screenshot (4331).png)
