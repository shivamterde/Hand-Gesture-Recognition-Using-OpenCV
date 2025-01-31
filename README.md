# Hand-Sign-Recognition-using-OpenCV
The proposed method utilizes a web camera to capture frames of hand gestures in a live video stream. These frames undergo grayscale conversion to enhance contrast, facilitating the identification of the region of interest.

A smoothing filter is then applied to the grayscale image, followed by thresholding through a binarization technique to effectively separate the hand sign from the background.

Next, the width and height of the detected hand are analyzed to determine its horizontal and vertical orientation. A bounding box is then created around the hand, and finger peaks are identified.

Using the positions of these finger peaks and the hand’s orientation, a unique 5-bit representation is assigned to the hand sign. This 5-bit code is then compared with predefined letter and number notations, enabling accurate gesture recognition. Finally, the detected sign is converted into readable text, making it accessible to the general public.

