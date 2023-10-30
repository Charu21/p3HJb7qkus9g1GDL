# p3HJb7qkus9g1GDL

# Mon Reader

## Problem statement:

Our company develops innovative Artificial Intelligence and Computer Vision solutions that revolutionize industries. Machines that can see: We pack our solutions in small yet intelligent devices that can be easily integrated to your existing data flow. Computer vision for everyone: Our devices can recognize faces, estimate age and gender, classify clothing types and colors, identify everyday objects and detect motion. Technical consultancy: We help you identify use cases of artificial intelligence and computer vision in your industry. Artificial intelligence is the technology of today, not the future.

MonReader is a new mobile document digitization experience for the blind, for researchers and for everyone else in need for fully automatic, highly fast and high-quality document scanning in bulk. It is composed of a mobile app and all the user needs to do is flip pages and everything is handled by MonReader: it detects page flips from low-resolution camera preview and takes a high-resolution picture of the document, recognizing its corners and crops it accordingly, and it dewarps the cropped document to obtain a bird's eye view, sharpens the contrast between the text and the background and finally recognizes the text with formatting kept intact, being further corrected by MonReader's ML powered redactor.

MonReader is a new mobile document digitalization experience for the blind, for researchers and for everyone else in need for fully automatic, highly fast and high-quality document scanning in bulk. It is composed of a mobile app and all the user needs to do is flip pages and everything is handled by MonReader: it detects page flips from low-resolution camera preview and takes a high-resolution picture of the document, recognizing its corners and crops it accordingly, and it dewarps the cropped document to obtain a bird's eye view, sharpens the contrast between the text and the background and finally recognizes the text with formatting kept intact, being further corrected by MonReader's ML powered redactor.


## Data Description:

We collected page flipping video from smart phones and labelled them as flipping and not flipping.

We clipped the videos as short videos and labelled them as flipping or not flipping. The extracted frames are then saved to disk in a sequential order with the following naming structure: VideoID_FrameNumber

## Goal(s):

Predict if the page is being flipped using a single image.

## Success Metrics:

Evaluate model performance based on F1 score, the higher the better.

# Method and Results
1. Imported data from different folders and Preprocessed the image data, i.e normalizing, resizing, etc.
2. Applied Deep Learning, i.e, created an appropriate model CNN and trained the network with appropriate loss function for training and validation
3. Finally, the model performance was evaluated on accuracy and F1 Scores which were understood through graphs over the epochs.
4. And as a bonus step , using our created model, I also predicted a sequence of images generated manually with a phone contained an action of flipping or not.

## Conclusion

The best accuracy and f1 score were attained for the CNN model with 2 convolution layers, 2 maxpooling layers, 1 dropout layer and 3 dense layers with 99.5% accuracy, F1: 100%.


