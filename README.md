# Description
Used transfer learning to develop models which first distinguish between Pakistan CNIC and passport images and then detect bounding boxes around 5 selected classes which are first name, last name, date of birth, gender and card number.


# Procedure 
1. Collected 20 images from google images
2. Annotated the images using CVAT which is an online free to use annotation tool
3. Performed data augmentation which included gaussian blur and rotating the image by 4 degrees each time until 360 degrees
4. Built first model to distinguish between Pakistan CNIC and passport images.
5. Built second model to detect bounding boxes on CNIC images
6. Built third model to detect bounding boxes on passport images 


# Dependencies
1. Mask RCNN version 1.4
2. Tensorflow version 1.6
3. Numpy version 2.1

