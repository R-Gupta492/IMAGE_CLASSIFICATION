# IMAGE_CLASSIFICATION
The aim of this project is to classify the images of the cricketers . 
## TRAINING DATA 
no. of images: 576
no of players: 15

## TRAINING
The images were rando mly rotaded , flipped and there colour saturation and brightness were changed randomly to augment the data.

training data size: 300
validation data size: 276

## RESULTS
Accuracy acheived: 0.9435

## LEVEL 2
The images were captured from webcam by using openCv.
the faces were cropped out from the the above images using cascading_haar filter.
the above faces were fed to the trained model and top three predictions were taken.

