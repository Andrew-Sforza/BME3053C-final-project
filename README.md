# BME3053C-final-project
Machine identification of grimace scale in test rats.

This program aims to use an image of a rat's face to determine the degree to which it is in pain for laboratory settings. The code itself uses a simple thresholding function to make its decision.

Use the code RatEye_Thresholding, copy and paste the code into MATLAB or open the file in MATLAB, and insert the desired image's filename (.jpeg, .png, .tif). The code will then produce a result indicating if the rat is in pain based on the photo. Note, this is only for head-on images of the rat. The code determines the ratio of the rat eye's major and minor axis and uses that information to determie if the rat is in pain. 

Furthermore, we used an LDA analysis to determine the ratio that will differentiate between a rat in pain and not in pain which is seen in the code Rad_LDA_Analysis
