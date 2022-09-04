BREAST CANCER DETECTION USING CLASSIFICATION ALGORITHMS
 PRIYANSHU GUPTA
 203149
 NIT Warangal

Machine Learning Classification Algorithms Used:
1. Logistic Regression
2. Naive Bayes
3. Decision Trees
4. Random Forests
5. K-Nearest Neighbors
6. Support Vector Machines


Dataset Used:
1. Breast Cancer Detection - Wisconsin Breast Cancer Dataset
2. UCI Machine Learning Repository: Breast Cancer Wisconsin (Diagnostic) Data Set


PROJECT DESCRIPTION

Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.
The key challenges against it’s detection is how to classify tumors into malignant (cancerous) or benign (non cancerous).
This data was donated by researchers of the University of Wisconsin and includes the measurements from digitized images of fine-needle aspirate of a breast mass.
The breast cancer data includes 569 examples of cancer biopsies, each with 32 features. One feature is an identification number, another is the cancer diagnosis and 30 are numeric-valued laboratory measurements. The diagnosis is coded as "M" to indicate malignant or "B" to indicate benign.
The other 30 numeric measurements comprise the mean, standard error and worst (i.e. largest) value for 10 different characteristics of the digitized cell nuclei, which are as follows:-
Radius
Texture
Perimeter
Area
Smoothness
Compactness
Concavity
Concave Points
Symmetry
Fractal dimension
 
CONCLUSION

|   S.No. │ Classification Model      │   Model Accuracy │   Validation Accuracy │   Standard Deviation │
╞═════════╪═══════════════════════════╪══════════════════╪═══════════════════════╪══════════════════════╡
│       1 │ Logistic Regression       │            97.37 │               96.5111 │              5.5556  │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│       2 │ Linear SVC                │            97.37 │               97.4222 │              4.59436 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│       3 │ Kernel SVC                │            98.25 │               97.3778 │              5.17239 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│       4 │ 1 Nearest Neighbors       │            94.74 │               94.9333 │              7.40757 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│       5 │ 3 Nearest Neighbors       │            97.37 │               96.9333 │              5.83967 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│       6 │ 5 Nearest Neighbors       │            97.37 │               96.2667 │              6.08077 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│       7 │ 7 Nearest Neighbors       │            97.37 │               96.9333 │              4.92191 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│       8 │ 9 Nearest Neighbors       │            95.61 │               97.8222 │              4.36009 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│       9 │ 11 Nearest Neighbors      │            94.74 │               97.6    │              4.52352 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│      10 │ Gaussian Naive Bayes      │            95.61 │               93.1778 │              7.88814 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│      11 │ Decision Tree             │            92.11 │               92.5333 │              8.64681 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│      12 │ Random Forest (10 trees)  │            94.74 │               96.2667 │              5.66017 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│      13 │ Random Forest (25 trees)  │            96.49 │               95.8222 │              5.78444 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│      14 │ Random Forest (50 trees)  │            95.61 │               95.8222 │              6.19661 │
├─────────┼───────────────────────────┼──────────────────┼───────────────────────┼──────────────────────┤
│      15 │ Random Forest (100 trees) │            95.61 │               96.4889 │              5.58375 │

We can see that the validation accuracy is higher in 9 Nearest Neighbors. However, on comparing the models - Kernel SVC and 9 Nearest Neighbors we can see that the Training accuracy and Validation accuracy is stable in Kernel SVC model (less standard deviation). Hence, we use the model Kernel SVC for Breast Cancer Detection.
Hence our recommended model - Kernel SVC provides a model accuracy of 98.25 percent and a validation accuracy of 97.38 percent.
 


