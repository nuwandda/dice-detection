# dice-detection
Identify the number of black and white dice and their value

## Steps: 
  1. Convert image to Gray
  2. Apply Gaussian blurin order to soften image
  3. Use threshold to reduce the information of image 
  4. To ind the boundaries, I used Canny Edge Detection Algorithm
  5. Find contours of the prepared image (We set the external to get only external contours)
  6. Create a region of interest with using the contours area
  7. Apply Blob Detector to find keypoints and find the value of dice (There will never be a perfect pip. So, I defined minimum      inertia 0.5.)


