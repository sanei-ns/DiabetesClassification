# DiabetesClassification


To run this program, use the code present in classify.py and dataset which can be obtained from https://www.kaggle.com/saurabh00007/diabetescsv or directly from the repo.
 * Place the data set and DiabetesClassificationUsing_KNN_DT_SVM.ipynb file in the same directory.
 * Run DiabetesClassificationUsing_KNN_DT_SVM.ipynb .
**** In the code, the comments explains what each section does ****

## Classifiers
The classifiers used in the program are:
  * KNN (k-nearest neighbors)
  * DesisionTree
  * RandomForest
  
For obtaining best accuracy for KNN,DecisionTree & Random Forest we tried different values of hyperparameter. For each classifier’s value of hyperparameter we calculated the accuracy and picked the value which gave the maximum accuracy. 

By analysis of four different classification methods which are random forest, DeceisionTree and KNN algorithm. Out of these algorithms used the maximum accuracy obtained was of KNN classification due to the nature of data given,the data set size was large so KNN could find more neighbors and the varied number of features in the dataset making it manageable and providing best execution with KNN. We obtained a maximum accuracy of 78.354978% .
