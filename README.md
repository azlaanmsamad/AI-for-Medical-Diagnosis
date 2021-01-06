# AI-for-Medical-Diagnosis

## Description:

This repo is divided into 3 parts:
1. [Disease detection with computer vision](https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/tree/master/Disease%20detection%20with%20computer%20vision)
2. [Evaluating models](https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/tree/master/Evaluating%20models)
3. [Image segmentation on MRI images](https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/tree/master/Image%20segmentation%20on%20MRI%20images)



The first part [Disease detection with computer vision](https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/tree/master/Disease%20detection%20with%20computer%20vision) deals with the following things:
* Data pre-processing: checking for data leakage
* Preprocess images properly for the train, validation and test sets
* Implement a weighted loss function to address class imbalance.
* Set up a pre-trained neural network to make disease predictions on chest x-rays.

The Second part [Evaluating models](https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/tree/master/Evaluating%20models) addresses the following topics:
* Calculate true positives, true negatives, false positives, false negatives.
* Calculate sensitivity and specificity
* Calculate Positive Predictive Value (PPV) and Negative Predictive Value (NPV).
* Understand confidence intervals, ROC curve, and F1 score.

The Third part [Image segmentation on MRI images](https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/tree/master/Image%20segmentation%20on%20MRI%20images) deals with the following topics:
* Perform image segmentation on 3D MRI data.
* Take random sub-samples from a 3D image.
* Standardize an input image.
* Apply a pre-trained U-Net model.
* Implement a proper loss function for model training (soft dice loss).
* Evaluate model performance by calculating sensitivity and specificity.

## Notebooks:

There are following notebooks:
* [Chest X-Ray Medical Diagnosis with Deep Learning](https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/blob/master/Disease%20detection%20with%20computer%20vision/Chest%20X-Ray%20Medical%20Diagnosis%20with%20Deep%20Learning.ipynb):
...This notebook is used to achieve the following tasks:
..* Pre-process and prepare a real-world X-ray dataset
..* Use transfer learning to retrain a DenseNet model for X-ray image classification
..* Learn a technique to handle class imbalance
Measure diagnostic performance by computing the AUC (Area Under the Curve) for the ROC (Receiver Operating Characteristic) curve
Visualize model activity using GradCAMs
* [Evaluation of Diagnostic Models](https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/blob/master/Evaluating%20models/Evaluation%20of%20Diagnostic%20Models.ipynb)
* [Brain Tumor Auto-Segmentation for Magnetic Resonance Imaging (MRI)](https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/blob/master/Image%20segmentation%20on%20MRI%20images/Brain%20Tumor%20Auto-Segmentation%20for%20Magnetic%20Resonance%20Imaging%20(MRI).ipynb)



https://github.com/azlaanmsamad/AI-for-Medical-Diagnosis/blob/master/Disease%20detection%20with%20computer%20vision/Chest%20X-Ray%20Medical%20Diagnosis%20with%20Deep%20Learning.ipynb
