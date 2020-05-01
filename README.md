# Chest-X-Ray-Abnormality-Classification
This projects aims to detect abnormalities in chest X-rays using methods in Deep Learning. 

## Tasks
- [X] Create a Dataset parser
  - [X] Visualize images
  - [X] Explore class imbalance
  - [X] Process labels (one-hot encoding, reassigning labels, etc.)
- [X] Binary classification
  - [X] Create generators for train and validation splits
  - [X] Train using a VGG-style neural network
  - [X] Use transfer learning (InceptionResNetv2)
  - [X] Plot training graphs (Accuracy, Loss)
- [X] Multilabel classification
  - [X] Create generators for train and validation splits
  - [X] Without sampling: Train using a MobileNet pretrained on ImageNet
  - [X] With sampling: Train using a MobileNet pretrained on ImageNet
  - [X] Plot training graphs (Accuracy, Loss, ROC-AUC)
  
## Technical specifications
The notebook is written in Python3 and uses the following major libraries/frameworks:
1. Deep Learning framework: Keras
2. Data processing: Numpy, Pandas, Scikit-learn
3. Data visualization: Matplotlib, OpenCV

## Source
The data has been taken from the [NIH Chest X-ray Dataset](https://www.kaggle.com/nih-chest-xrays/sample) on Kaggle.

## References
1. [Monk AI's example notebook on multiclass classification using Satellite images](https://github.com/Tessellate-Imaging/monk_v1/blob/master/study_roadmaps/4_image_classification_zoo/Multi%20label%20Image%20classification%20-%20Satellite%20Image%20tiles.ipynb)
2. [Scott Mader's notebook on multilabel classification of chest x-rays](https://www.kaggle.com/kmader/train-simple-xray-cnn)
3. [Paul Mooney's notebook on predicting pathologies in X-Ray images](https://www.kaggle.com/paultimothymooney/predicting-pathologies-in-x-ray-images)

