# Kaggle Competitions
My solutions to challenges shared by [Kaggle](https://www.kaggle.com/competitions)

## [Titanic](https://www.kaggle.com/c/titanic)
**Goal**: Predict whether a passenger on the Titanic survived given the passenger's age, sex, passenger class, and other features.

My solution did not compare particularly well to other submissions, but it was an enjoyable first Kaggle competition as I got to practice my skills.

My solution incorporates:
- Data visualization
- Feature engineering
- Logistic regression

Key libraries: pandas, numpy, matplotlib, seaborn, sklearn

## [MNIST digit recognizer](https://www.kaggle.com/c/digit-recognizer)
**Goal:** Classify hand-written digits (0-9) from 28x28 images.

This challenge was a fun exercise in data augmentation. Although my CNN performed well on the provided dataset (>98% accuracy), augmenting the training data increased the model's accuracy. The augmentations I incorporated were random rotations, horizontal/vertical shifts, Gaussian blur, and additive pixelated noise.

My solution incorporates:
- Convolutional neural networks
- Data augmentation

Key libraries: numpy, sklearn, tensorflow/keras, PIL, cv2
