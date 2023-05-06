# Celeb-Image-Coloring-Using-GAN

The aim of this notebook is to generate coloured image, given a grayscale image as input.

For the training of the model I had to create this dataset, wherein gray scale images are taken as input and a and b components of LAB color space are taken as output.

I used the base Pix2Pix GAN model for image colourisation. And as stated by the authors of this paper, a fraction of the images generated were desaturated. To mitigate the lack of colourfulness, this model architecture was proposed.

Generated Video:- 



https://user-images.githubusercontent.com/88615645/236622551-ead6e6f9-60ce-4e4a-a03f-74d4b86bc2de.mp4

