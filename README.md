# Hand-Written-Captcha-recognition
This is a Ml-based model that takes captcha images as input and then predicts the handwritten characters written in it. OpenCv library was used for image pre-processing for image segmenation and CNN model for predicting segmented parts of given captcha.

Approach:
# To extract letters and captcha images we have used python computervision library opencv.
# Using the segmentation code (img_cleaning(), read()) ->
	1. Segment letters from digital images as well as handwritten images
	2. Can read colorful images(red,blue,black text on white background)
	3. To some extend the code also segments shadowed images
	4. Can also segment letters in the presence of noise

# For training the model we have used CNN 
	Loss is evaluated using Cross Entrophy loss 
	Optimizer used is Adam

