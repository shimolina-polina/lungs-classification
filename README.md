# lungs-classification
Lungs classification into 2 classes: healthy and pneumonia

Dataset: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

The project aims to classify lungs into healthy and diseased categories using machine learning techniques. The dataset consists of chest X-ray images, which will be preprocessed and fed into a deep learning model for classification. The goal of is to create a reliable and accurate system for early detection and diagnosis of lung diseases, ultimately improving patient outcomes.

Models used:
1. CNN with three sets of convolutional and pooling layers, followed by two fully connected (Dense) layers. The input shape is a 3-channel image with dimensions of img_width by img_height. The output layer has one neuron with a sigmoid activation function, making it suitable for binary classification tasks.(lungs_classif.ipynb)
2. Pretrained VGG16 with added layers corresponding to the task of lung classification. (lungs_classif.ipynb)
3. Modified first model: Dropout layers, BatchNormalization layers, data augmentation, EarlyStopping. (final model.ipynb)

Accuracy of final model: 90,84%
