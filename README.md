# SkinDetection
Skin detection using HSV &amp; YCbCr color space (Python, OpenCV)

# About the precedure of detection
The above entire procedure is applied to each and every pixel of the image. 

The RGB image value is converted to HSV as well as YCbCr value, the HSV and YCbCr value of each pixel is compared to the standard values of a skin pixel and the decision is made whether the pixel is a skin pixel or not depending on whether
the values lie in a range of predefined threshold values for each parameter.

The ranges for a skin pixel used in this algorithm are as follows:

        0<=H<=17 and 15<=S<=170 and 0<=V<=255

				and
				
        0<=Y<=255 and 135<=Cr<=180 and 85<=Cb<=135
	

# Experimentation 

#### We have tested the perfomence of this methode using images from two diffrent database :

##### HGR (Hand Gesture Recognition) Image Database

URL : http://sun.aei.polsl.pl/~mkawulok/gestures/

![alt text](https://github.com/CHEREF-Mehdi/SkinDetection/blob/master/Image/ReadMeImages/ROC_HGR.png)

##### SFA (A Human Skin Image Database based on FERET and AR Facial Images) Image Database

URL : http://www.sel.eesc.usp.br/sfa/

![alt text](https://github.com/CHEREF-Mehdi/SkinDetection/blob/master/Image/ReadMeImages/ROC_SFA.png)

### In the following images you will see the result of skin detection of each color space separately and then the result of their association

![alt text](https://github.com/CHEREF-Mehdi/SkinDetection/blob/master/Image/ReadMeImages/result1.png)

![alt text](https://github.com/CHEREF-Mehdi/SkinDetection/blob/master/Image/ReadMeImages/result2.png)

![alt text](https://github.com/CHEREF-Mehdi/SkinDetection/blob/master/Image/ReadMeImages/result3.png)

### In the following images you will see the result of skin detection of this methode in the two databases SFA and HGR

![alt text](https://github.com/CHEREF-Mehdi/SkinDetection/blob/master/Image/ReadMeImages/all_detection.png)




