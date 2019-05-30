# Style-Transfer-using-Pytorch

*Style Transfer* is  a method by which we can transfer the content of one image into the another image or convert to style(background impression)
of one image to match that of another. 

This notebook is completed as an assignment and makes use of **Pytorch** for to achieve the goals.

I have used 2 images here -a) An image of Joker (the famous anti-hero) b) A snap of one of the digital posters of the "Matrix" movie.

Image 'a' has been used as the content image, and 'b' as style image.  VGG architecture with pre-defined weights have been used initially to extract the features from both the images.
Features include the Content features as well as the Style features. The 1st, 2nd, 3rd, 4th Convolution blocks of the VGG model extrtacts the style from an image. The 5th Convolution block extracts the content from an image.

Using these knowledge, the Style Transfer task has been accomplished.
