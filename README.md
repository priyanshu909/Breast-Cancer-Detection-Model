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

![image](https://user-images.githubusercontent.com/109714752/188306235-ae2f0812-2458-4364-8a69-e8195ebb540c.png)

We can see that the validation accuracy is higher in 9 Nearest Neighbors. However, on comparing the models - Kernel SVC and 9 Nearest Neighbors we can see that the Training accuracy and Validation accuracy is stable in Kernel SVC model (less standard deviation). Hence, we use the model Kernel SVC for Breast Cancer Detection.
Hence our recommended model - Kernel SVC provides a model accuracy of 98.25 percent and a validation accuracy of 97.38 percent.
 


