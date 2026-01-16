# Brain Tumor Classification from MRI Images using Classical Machine Learning and EfficientNetB0 Transfer Learning
This project focuses on the classification of brain tumors from MRI images using both **classical machine learning algorithms** and **deep learning techniques**.  
In addition to traditional ML models, a **transfer learning–based EfficientNetB0** architecture was implemented and evaluated to improve classification performance.

## Objectives
- Automatically classify brain tumors from MRI images  
- Compare classical machine learning models with deep learning approaches  
- Analyze the impact of **EfficientNetB0 transfer learning** on performance  

 ## Dataset
 **Source:** [https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset]
 
 **Total Images:** 7,023

 **Classes:** Glioma, Meningioma, Pituitary, No Tumor

 ## Sample MRI Images
 ![](images/sampleMRIimages.png)

 ## Methodology
1. Image preprocessing (resizing, normalization)  
2. Data augmentation to improve generalization  
3. Feature extraction and training using classical ML models (Logistic Regression, KNN, SVM, Naive Bayes, Decision Tree, AdaBoost, Random Forest)  
4. Transfer learning with **EfficientNetB0**
5. The models were evaluated using both hold-out validation and k-fold cross-validation.  
6. Performance evaluation and comparison

## Results (Top 2 Models)

| Model | Hold-Out Acc | Hold-Out F1 | K-Fold Acc | K-Fold F1 |
|------|-------------|-------------|------------|-----------|
| Random Forest | 0.933 | 0.928 | 0.925 | 0.922 |
| EfficientNetB0 | **0.947** | **0.943** | **0.908** | **0.904** |



## Training Performance
![Training Loss](images/loss_curve.png)

The training and validation accuracy curves show a consistent improvement over epochs, while the loss curves decrease steadily. 
The close alignment between training and validation results indicates stable learning without significant overfitting.

 ## Project Report
📎 **Full Project Report (Turkish):**  
[Brain Tumor Analysis Report (PDF)](report/Brain_Tumor_Analysis_Report_TR.pdf)

## Author
**Muhammed Doğru**  
Computer Engineering Student
