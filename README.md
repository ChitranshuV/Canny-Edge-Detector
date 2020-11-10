# Canny-Edge-Detector

This project was an assignment as a part of my course EE6132 - Modern Computer Vision assignment. The objectives of the following assignment are as follows:

- Read the image ‘clown.jpeg’ and display it.
- Convert it into a grayscale image.
- To suppress the noise use a Gaussian kernel to smoothen it. Keep the kernel size as 5 × 5
and sigma = 1.5.
- Apply the standard Sobel operator Gx and Gy discussed in class. Display the filtered
outputs. Also show the gradient magnitude and angle images.
- Apply non-maximum suppression as discussed in class. The exact method requires computing the imaginary pixels shown in gray in the image below using interpolation methods
such as bilinear and bicubic interpolation. As a simplification just locate the image pixels
- Instead of using the Double thresholding Hysteresis used in the exact algorithm simply
do a single thresholding operation. Pixels with values less than the threshold should be
suppressed. Use the median value of the magnitude image computed in Step 4 as the
threshold value. Show the final output.
- Repeat the above question but increase the sigma of the Gaussian kernel to 3. Choose your
filter size appropriately. Just show the final output for this question. How does the final output
differ from that of the previous question?
