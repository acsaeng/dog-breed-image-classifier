# Kaggle's Dog Breed Identification Competition

**Authors:** Brandon Attai, Tahsin Chowdhury, Kelten Falez, Timothy Mok, Aron Saengchan, and Jimmy Zhu

## Summary
Convolutional neural networks (CNN) have proven to be one of the most valuable tools for image analysis and classification tasks. Building upon a shared-weight architecture known as feature maps, CNN models can sometimes require significant time and effort to train and tune properly in providing useful results. This study reports the results of training and applying two popular CNN models in the classification task of a collection of dog breed images – ResNet50 and VGG16. A series of systematic tests were performed to optimize and achieve higher validation accuracies. To further extend these methods, the best iterations were ensembled together by capturing the feature maps of each model. The results of these CNN models were also tested against automated machine learning methods, performed using the AutoKeras and AutoGluon frameworks, with the benefits and drawback of each being evaluated. Gradient-weighted Class Activation Mapping (GradCAM) was applied to visualize how select models progressively analyzed the provided input images in arriving to generalized predictions.

*This project was completed as part of ENEL 645: Data Mining & Machine Learning at the University of Calgary.*