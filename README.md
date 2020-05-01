# Chest-X-Ray-Abnormality-Classification
This projects aims to detect abnormalities in chest X-rays using methods in Deep Learning. 

## Tasks
- [ ] Create a Dataset parser
  - [ ] Visualize images
  - [ ] Explore class imbalance
  - [ ] Process labels (one-hot encoding, reassigning labels, etc.)
- [ ] Binary classification
  - [ ] Create generators for train and validation splits
  - [ ] Train using a VGG-style neural network
  - [ ] Use transfer learning (InceptionResNetv2)
  - [ ] Plot training graphs (Accuracy, Loss)
- [ ] Multilabel classification
  - [ ] Create generators for train and validation splits
  - [ ] Without sampling: Train using a MobileNet pretrained on ImageNet
  - [ ] With sampling: Train using a MobileNet pretrained on ImageNet
  - [ ] Plot training graphs (Accuracy, Loss, ROC-AUC)

## Source
The data has been taken from the [NIH Chest X-ray Dataset](https://www.kaggle.com/nih-chest-xrays/sample) on Kaggle.

## References
1. [Monk AI's example notebook on multiclass classification using Satellite images](https://github.com/Tessellate-Imaging/monk_v1/blob/master/study_roadmaps/4_image_classification_zoo/Multi%20label%20Image%20classification%20-%20Satellite%20Image%20tiles.ipynb)
