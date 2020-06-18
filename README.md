# **NeuralStyleTransfer**
#### requirements:
1. Tensorflow >= 2.0.0
2. NumPy == 1.18.5
3. Matplotlib == 3.2.2
3. Pillow == 7.1.2

Neural style transfer is an optimization technique used to take two images—a content image and a style reference image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.
This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network.
For example, let’s consider a content image and a style image,

<center><img src="content.jpg" alt="content" width="400"/> <img src="style.jpg" alt="style" width="350"/><br></center>

The image on the left is the content image and the image on the right is the style image.

Now, after applying the neural style transfer, the generated image would look something like this,
<center><img src="generated.jpg" alt="content"/></center>

Check out the Jupyter notebook for the implementation.