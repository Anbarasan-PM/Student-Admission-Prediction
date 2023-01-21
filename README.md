# Student-Admission-Prediction

## problem statement :
                A student who completed his/her high school have a probelm in selecting a college and course.Using machine learning algorithms this probelm could be solved.
 
 
 ## Steps :
        * Importing libraries and reading data (csv file).
        * Extracting useful insights using describe,shape...
        * Visualizing how the variables are distributed.
        * Outliers detection(if present).
        * Encoding categorical variables.
        * Feature extraction.
        * Spliting of data.
        * Data Handling (Oversampling & Undersampling).
        * Cross validations.
        * Applying suitable algorithms.
        * Performance Measurement.
        * Interpretation.
## Algorithms used:
       note : target variable is categorical variable (yes(1)/no(0)) type. Whether the student will select or not select.
      Logistic Regression:
                         A classification algorithm which is used to find the probability of success and events.It lerans a linear relationship from the data provided and introduces a non-linearity relationship using sigmoid function.
                            sigmoid function is represented by :
                                                          f(x) = 1/(1+exp(-beta*x)
                                                          
                 Disadvantages :
                    number of features > number of observations it ,the algorithm leads to overfts.
                    non-linear probelms cannot be solved, because the boundary is linear.
                    
                 Assumptions :
                   * Independence of errors.
                   * Linearity in the logit for continuous variables.
                   * Absence of multicollinearity.
                   * Lack of strongly influential outliers.
        
      Decision Tree Classifier:
                              A hierarchical structure which is used to predict continuous or classify categorical variables.A "if-else" condition is used for each node in the tree to classify and the edges is to move the next state.
                          
                      Disadvantages :
                          * Sensitive to outliers.
                          * A problem of overfitting.
                      Assumptions :
                          * Statistical methods are used to oredering the variables as root node or internal node.
                          * Feature values are preferred to be categorical.
                          * Based on the attributes values records are distributed recurvesily.
      Support Vector Machine :
              A supervised learning algorithm which is used for both classification and regression problems.The objective of SVM algorithm is to find a hyperplane in an N-dimensional space that distinctly classifies the data points.
              
                     Disadvantages :
                        * Not good for the data has more outliers, noise.
                        * Performs poorly in imbalanced datasets.
                     Assumptions :
                        * The margin should be as large as possible.
                        * The support vectors are the most useful data points because they are the ones most likely to be incorrectly classified.
      Random Forest :
                Random Forest is an ensemble learning technique ,which the target is predicted baed on majaority of votes from each bagging of models.
                
                        Advantages :
                           * No sensitive to outliers.
                           * No problem of overfitting.
                           * Accuracy high.
                           * Handle large datasets.
                        Disadvantages :
                           * High computation required.
                           * High resources required.
                        No formal distributional assumptions.
                        note : Missing values should be handled from training the model.

## Interpretation :
       However the data is imbalanced , metrics should be considered is F beta score,where beta =1
                        By comparing the f1 metric of the four classification models "random forest" calssifier gives the best score.
                        Random Forest Classification algorithm is best suitable for this problem and the results is displayed in accuracy_score_graph  [https://github.com/Anbarasan-PM/Student-Admission-Prediction/blob/main/accuracy_comparison_graph.png]().
        
           
                      
     
                   
                           
                               
                
       
                         
        
  
