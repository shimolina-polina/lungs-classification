# lungs-classification
Lungs classification into 2 classes: healthy and pneumonia

The aim of this study is to develop and train a highly accurate machine learning model for the classification of lungs into two classes: pneumonia patients and healthy individuals.

A Convolutional Neural Network (CNN) method is employed in this work for the classification of lung images into two classes: pneumonia patients and healthy individuals.

A dataset comprising lung images of patients was used to train the models, which were divided into two categories: training and testing(80:20). The input images were resized to a consistent size and normalized.

After training, the model was tested on a separate test dataset, and its accuracy was evaluated. Recall, Precision, and F1-score were selected as metrics since the data exhibits a small but acceptable class imbalance, and it is important to assess how accurately the model predicts the presence of pneumonia.

Training the final model resulted in the following maximum performance metrics: Test loss: 0.1271, Test Accuracy: 0.9555, Test F1-score: 0.9686, Test recall: 0.9762, Test Precision: 0.9622.

|File|Content|
|-|-|
|[lungs-1.ipynb](https://github.com/shimolina-polina/lungs-classification/blob/main/lungs-1.ipynb "View file")|Basic CNN model|
|[lungs-2.ipynb](https://github.com/shimolina-polina/lungs-classification/blob/main/lungs-2.ipynb "View file")|Additional batch normalization layers added|
|[lungs-3.ipynb](https://github.com/shimolina-polina/lungs-classification/blob/main/lungs-3.ipynb "View file")|Dropout layer added|
|[lungs-classif.ipynb](https://github.com/shimolina-polina/lungs-classification/blob/main/lungs_classif.ipynb "View file")|Pretrained VGG-16 (another dataset)|
