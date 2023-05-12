# Image Filters and Transformations
This project focuses on applying various image filters and transformations using computer vision techniques. The goal is to extract useful information from digital images and enhance or modify them to improve visual analysis and interpretation. The project covers different types of filters and transformations and provides examples and results for each.

**Part 1: Image Effects and Filters**
In this section, several photo effects and filters are applied to images captured. The following filters are implemented:

**1.	Contrasting:** Enhances the colors and brightness of an image by adjusting pixel values based on their frequency distribution.

**2.	Inverting:** Reverses the colors in an image, making dark colors appear light and vice versa. Useful for improving visibility or analyzing images.

**3.	Separating RGB: Splits an image into its red, green, and blue color channels to examine each separately.

**4.	Solarizing:** Removes excessive brightness in an image, creating a contrast effect. Useful for correcting overexposed images.

**5.	Binarizing:** Converts an image into a binary representation by setting a threshold value. Useful for segmenting images and locating objects.

**Part 2: Image Filtering Techniques**

In this section, different image filtering techniques are explored to achieve specific effects. The following filters are implemented:

**1.	Mean Filtering:** Smooths an image by replacing each pixel with the average value of its neighboring pixels. Various window sizes are used to observe the impact on image clarity and detail.

**2.	Gaussian Filtering:** Blurs an image using a weighted average of neighboring pixels, with more weight given to the central pixel. Different window sizes are used to control the blur effect.

**3.	Median Filtering:** Removes noise from an image while preserving edges by replacing each pixel with the median value of its neighboring pixels.

**4.	Sobel Filtering:** Identifies edges in an image by convolving it with a Sobel filter. Separate filters are applied to the red, green, and blue color channels.

**5.	Local Binary Pattern (LBP):** Identifies textures and edges by thresholding and analyzing the binary values of neighboring pixels.


**Part 3: Image Transformations**

This section focuses on image transformations using Fourier transform and other techniques. The following transformations are implemented:

**1.	Vertical Fourier Transform:** Emphasizes the vertical components of an image by reducing the effect of horizontal components. The masked Fourier image highlights the frequency components in the image.

**2.	Horizontal Fourier Transform:** Enhances the horizontal components of an image by reducing the effect of vertical components. The resulting masked Fourier image reveals the dominant frequency directions.

**3.	Low Pass Blurring:** Applies a low-pass filter to an image, blurring it by averaging each pixel with its neighboring pixels. This technique helps reduce noise in an image.

**4.	Sub-sampling:** Reduces image resolution by a given factor, helping to process high-resolution images more efficiently. The image is sampled according to the specified factor.

**5. Gamma Correction:** Adjusts the brightness of an image to compensate for differences in how cameras record and display images. Gamma correction enhances image quality by improving brightness levels.

