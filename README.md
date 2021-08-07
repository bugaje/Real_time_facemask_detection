# Real_time_facemask_detection
Real time face-mask detection using Deep Learning and OpenCV

This project uses a Convolutional Neural Network, to differentiate between images of people with mask and without masks. The CNN manages to get an accuracy of 96.7% on the training set and 97.2% on the test set. Then the stored weights of this CNN are used to classify as with mask or no mask, in real time, using OpenCV. With the webcam capturing the video, the frames are preprocessed and and fed to the model to accomplish this task. 

The model is capable of predicting multiple faces with mask or without masks at the same time.
