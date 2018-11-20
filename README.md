# SkinDetection
Skin detection using HSV &amp; YCbCr color space (Python, OpenCV)

# About the precedure of detection
The above entire procedure is applied to each and every pixel of the image. 

The RGB image value is converted to HSV as well as YCbCr value, the HSV and YCbCr value of each pixel is compared to the standard values of a skin pixel and the decision is made whether the pixel is a skin pixel or not depending on whether
the values lie in a range of predefined threshold values for each parameter.

The ranges for a skin pixel used in this algorithm are as follows:

        0<=H<1=7 and 15<=S<=170 and 0<=V<=255

				              and
				
        0<=Y<=255 and 135<=Cr<=180 and 85<=Cr<=135
