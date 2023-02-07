# Dental-Cavity-Diagnosis
Hey Everyone! this is a model built to distinguish images of Caries and Non-Caries... <br /><br />
first, gathering Data <br />
we collected OPG images of Teeth from different hospitals in Coimbatore. <br /><br />
second, AUGUMENTATION <br />
we have about 500 images in caries and 434 in non-caries, which we augument and add back to the dataset, making it rise upto 900 each in caries and non caries. <br /><br />
Building Architecture, <br />
model consists of 7 convulutional layers and 6 max pooling layers that uses RELU function to process.The ANN layers have 2 hidden layers that uses relu and Sigmoid (binary classification) to bring the output.
<br />
I used binary_crossentropy as loss function and optimizer as adam.<br /><br />
model is fit for 12 epochs after which it gives an accuracy of 82.76%
<br/>
</br>
UPDATE:
</br>
  Uploaded another remake of this project increasing each class upto 1000, using Augmentor. </br>
  Augmentor is a Python package designed to aid the augmentation and artificial generation of image data for machine learning tasks. </br>
  The developed Model has shown good Generalizability and Prediction.</br>
  I have included Early Stopping with Patience 3, training stopped at the 9th epoch. </br>
  Accuracy is about 98.4% 

