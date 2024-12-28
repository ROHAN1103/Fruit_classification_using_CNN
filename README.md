Fruit_classification_using_CNN

  This project involves the classification of fruits into three classes: Peach, Pomegranate, and Strawberry. The image dataset is organized into three folders: train, test, and validation, each containing images for the three classes. The dataset is structured as follows:

![DALL·E 2024-12-28 21 21 43 - A vibrant still life featuring a peach, a strawberry, and a pomegranate  The peach is ripe and slightly fuzzy, the strawberry is red and glossy with a](https://github.com/user-attachments/assets/c81f8ca2-3e60-486a-963f-9ebd6e76b394)


* Training Set: 75 images per class.

* Testing Set: 50 images per class.

* Validation Set: 25 images per class.

Dataset Structure:

![image](https://github.com/user-attachments/assets/f2bc46c1-8a13-4a83-8b86-e5852e61048a)

**Preprocessing Steps:**
* Scaling a images.
* Resizing the images.

**Building a MachineLearning model:**
* Model used: CNN
* Layers:
*         *  Input layer is CNN with "relu" as a activation function.
          *  Maxpooling layer.
          *  CNN with "relu" as a activation function.
          *  Maxpooling layer
          *  CNN with "relu" as a activation function.
          *  Maxpooling layer
          *  Flatten layer
          *  dense layer with "relu".
          *  Dropout layers
          *  dense layer with "softmax" activation.
* Model is compiled with "adam" optimizer, "categorical_crossentropy" as a loss function and accuraccy metrics.
* Then model is trained with training and validating data.

**Training and validation accuraccy graph**

  ![434ed025-4cf2-48a3-8059-8d7715feb05b](https://github.com/user-attachments/assets/d12a9add-f6c0-4038-a563-920a25fcba5e)


  
