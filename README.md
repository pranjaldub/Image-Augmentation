# Image-Augmentation
Pytorch Custom image augmentation pipeline using ImgAug library and pytorch compose.
Augmentations used :

-Tensor conversion : Array to pytorch tensor conversion
-Normalization : rescaling image pixels in range [0,1]
-Flip : Mirroring the original image vertically and horizontally
-Affine :  geometric transformation that preserves lines and parallelism (but not necessarily distances and angles).
-Dropout/CoarseDropout : Randomly removing some pixels of images
-Hue and Saturation : Saturation can be thought of as the ‘amount’ of color in an image. Use the saturation parameter to control the amount of jitter in saturation, with value                         from 0 (no change) to 1 (potentially large change)
                      Hue can be thought of as the ‘shade’ of the colors in an image. Use the hue parameter to control the amount of jitter in hue, with value from 0 (no change)                       to 1 (potentially large change)
-Scale :  scaling image pixels
-Translate : adding value to images pixel to translate it either veritically of horizontally in either direction
-Rotate : Changing the alignment of image pixels without translating
-Shear : Shear tool is used to shift one part of an image, a layer, a selection or a path to a direction and the other part to the opposite direction. For instance, a horizontal          shearing will shift the upper part to the right and the lower part to the left. A rectangle becomes a diamond.
-Bilinear Interpolation : The key difference in bilinear interpolation is that it uses 4 nearest neighbors to generate an output surface.
                          On the other hand, cubic convolution uses 16 nearest neighbors which smooths the surface more so.
                          Bilinear interpolation assumes input is continuous.
                          This resampling method uses a distance-average to estimate with closer cells being given higher weights.
-Random Brightness : randomly increase the value of some pixels
-Images to their superpixel conversion
-Blur : Averages rapid changes in the pixel intensity
  =>Gaussian Blur
  =>Average Blur
  =>Median Blur
-Sharpening
-Embossing
-Edge detection :
  =>Simple edge detection
  =>Directed edge detection
-Additive Gaussian Noise
-Image channel inversion
-Per pixel value addition
-Per pixel multiplication
-Grayscale conversion
-Elastic Transformation
-Piecewise affine
