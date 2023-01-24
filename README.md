#  Image classification using CNN for Diabetic Retinopathy


## Background
Diabetic Retinopathy is disease of the eyes 
    -caused by high blood sugar
    -Affects blood vessels
    -Causes Loss of Vision
    - Measured by Disease Proliferation

Affects individuals with diabetes

Found in 4.1 million people
    -Roughly 1/29 diabetics
    -1/3 are African-American and Mexican-American



## Business Problem
We are building a deep learning model to detect the various levels of diabetic retinopathy

  Why?
  
Medical misdiagnosis caused by varying legels of knowledge and experience

Ensuring proper diagnosis for medical professional

## Data
Data is created by TensorFlow

Contains images of 35,000+ images of different levels of Diabetic Retinopathy

## Methods
Images imported from directory

Baseline model created for comparison

Model evalution

Using Tranfer Learning, instantiating pre-trained model as base

Adding the base model to final model

Model Evaluation


## Results
Data Visualization for initial model accuracy
![](images/main_accuracy.png)

Data Visualization for initial model loss
![](images/main_loss.png)

Data Visualization of model with transfer learning performance accuracy
![](images/tl_accuracy.png)

Data Visualization of model with transfer learning performance loss
![](images/tl_loss.png)



## Conclusions / Summary of Findings
The model evaluation shows 68% Accuracy

Overfitting occus in both models

Transfer learning greatly improves model performance


## Next Steps...
1) Build Deep Learning models to other ocular diseases (e.g., Diabetic Macular Edema)

2) Pursue other areas of medicine, where we can track disease progression. (e.g., Cancer metastasis)

3) Use Deep learning to build models for disease detection (e.g., Pneumonia)





├── dataset : data used for modeling

├── images : images used in PPT and readme

├── README.md : project information and repository structure

├── dsc-phase-5-project-presentation.pptx : (Presentation for Stakeholders)

└── Diabetic Retinopathy Image Classification.ipynb (jupyter notebook used for modeling)

