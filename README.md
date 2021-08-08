# Real_time_facemask_detection
Real time face-mask detection using Deep Learning and OpenCV

This project uses a Convolutional Neural Network, to differentiate between images of people with mask and without masks. The CNN manages to get an accuracy of 96.7% on the training set and 97.2% on the test set. Then the stored weights of this CNN are used to classify as with mask or no mask, in real time, using OpenCV. With the webcam capturing the video, the frames are preprocessed and and fed to the model to accomplish this task. 

The model is capable of predicting multiple faces with mask or without masks at the same time.

WITH NO MASK 1
![no_mask1](https://user-images.githubusercontent.com/57234839/128627624-329a3dcf-b9db-493b-aef3-97f621df9314.PNG)
WITH NO MASK 2
![no_mask2](https://user-images.githubusercontent.com/57234839/128627634-c6c3973d-9f8f-4838-b430-f74c6a50647f.PNG)

WITH MASK 1
![with_mask1](https://user-images.githubusercontent.com/57234839/128627640-bddf4be7-3acd-47b5-bdd7-619d87da4698.PNG)
WITH MASK 2!
[Uploading with_mask2.PNG…]()
