# **K-Nearest Neighbors (KNN) Classifier for Car Evaluation Dataset**
This repository contains Python code implementing a KNN classifier for the car-evaluation dataset as part of a Machine Learning course project at the University of Ottawa in 2023.

Required libraries: scikit-learn, pandas, matplotlib.
Execute cells in a Jupyter Notebook environment.

## Multi-class classification problem

Task is to classify the car dataset into 4 classes: Unacceptable /Acceptable /Good /Very good.
### Independent Variables:
   +	Buying: buying price
   *	Maint: maintenance price
   +	Doors: numbers of doors
   *	Persons: capacity in terms of persons to carry
   +	Lug_boot: Size of luggage boot
   *	Safety: estimated safety of the car
### Target variable:
   +	Evaluation



## **Key Tasks Undertaken**

1. **Data Preparation:**
   - Organized a 1728-sample dataset into distinct subsets: 
     - Training (1000 samples),
     - Validation (300 samples), and
     - Testing (428 samples) using Python for accurate model assessment.
   ![merge_from_ofoct](https://github.com/RimTouny/KNeighborsClassifier/assets/48333870/c0888f24-0436-4f80-84ca-e85157e32760)


2. **Preprocessing:**
   - Transformed categorical string attributes into numerical representations, enabling the application of distance-based metrics, such as Euclidean distance, crucial for KNN classification.

3. **Exploring Training Sample Sizes:**
   - Investigated the influence of diverse training sample sizes (ranging from 10% to 100% of the training set) on model performance.
   - Evaluated and measured accuracy on both the validation and test sets, discerning the impact of varying training sample sizes on model accuracy.

        ![image](https://github.com/RimTouny/KNeighborsClassifier/assets/48333870/f9c03cff-4fce-4503-9dba-5055112666fd)
        ![image](https://github.com/RimTouny/KNeighborsClassifier/assets/48333870/e2e025a6-f983-48c9-895e-121a332a550a)

        - Using 10%-40% from the training set means, that the training set size is less than the validation and test set 
         size so validation and testing accuracy in these points are meaningless because the model didn’t train enough. 
        - From 50% - 100% our model starts to train well until reaches to 100% with the best validation and testing accuracy.  


3. **Optimization of K Value:**
   - Identified the most suitable K value (from 1 to 10) using the complete training set.
   - Visualized the effect of different K values through an accuracy curve plotted on the validation set, illustrating the performance variance of the KNN classifier.
     ![image](https://github.com/RimTouny/KNeighborsClassifier/assets/48333870/47d757ee-6621-4e92-9610-65a3059b3585)


