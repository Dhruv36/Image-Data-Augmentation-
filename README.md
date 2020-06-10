# Image Data Augmentation.
 
Augmentation means to build something great or increase the feature of something. Here we will perform Augmentation on Image Data using Keras ImageDataGenerator.  This class basically works by 1) Accepting a batch of images used for training 2) Applying a series of random transformation to image present in a batch. 3) This newly created batch is replaced with the original batch. 4) Training the Conventional Neural Network model on this newly created batch by random transformation.

There are three types of data augmentation in the context of computer vision
1) Dataset generation and data expansion via data augmentation (less common)
2) In-place/on-the-fly data augmentation (most common) also we have used this.
3) Combining dataset generation and in-place augmentation

In this Image data augmentation, we are trying to understand the use of ImageDataGenerator class with hands-on experience. we will perform geometric transformation like rotation, shear transformation, horizontal and vertical flips. After that we will train the model by giving the data augmented dataset. 

