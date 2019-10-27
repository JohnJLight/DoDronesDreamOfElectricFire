# DoDronesDreamOfElectricFire
Fire Detection Algorithim created for FireDrone.AI hackathon.
If you'd like to download my model check out releases.
The directory Whole_Images contains all images I collected in their original form.
The directory Training Data, contains all the images split into smaller sizes to train the NN on limited context as it was designed to be use by a drone. You'll notice there is not an equal number of images for both classes, and the smaller of the two was the limit for data used for both classes.
Images were randomly selected from the larger set to try to reduce human bias.
The model is a CNN built with Keras.

The notebook FireDrone_Submission.ipynb was used to submit for the various tests in the competition.

In the future I plan on returning to this project and possibly redoing it with segmentation and experimenting with various filters. Feel free to clone the data and experiment on your own.
