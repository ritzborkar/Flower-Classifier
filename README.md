# Flower-Classifier
Identifies flowers among 102 different flower categories

Training algorithm uses pre-trained Resnet18 for feature extraction. 
Classifier layers alone are then trained on V100 in AWS to achieve ~93% validation accuracy.
