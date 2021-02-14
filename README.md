# Spam detection
 
MultinomialNB implements the naive Bayes algorithm for multiunit distributed data and is one of the two classic naive Bayes variants used in text classification.
Based on the classical Naive Bayes, Q (yi) specifies the probability of occurrence of variable i of P (xi, y). The relevant address coding stage was taken as a reference for the application of the formulas. (https://scikit-learn.org/stable/modules/naive_bayes.html#multinomial-naive-bayes)<br>
Code details are presented in the code as a comment line.<br>

Basically, the steps taken are as follows;<br>
-Purification of data from unwanted characters<br>
-Removing words<br>
-Spam and raw data probability calculation<br>
-Train process and realization of test process (application of the specified formula)<br>
-Getting the predicted values of TN, FN, TP, FP<br>
-Extraction of results as Accuracy, Precision, Recall, F-Measure<br>

Train data was used as presented in the given file, while test data was used in a single file for spam and raw data.<br>

In the project, data capture and printing, data processing, ready-made classifier functions, packages and libraries other than standard data structures were not used.<br>

<b>The results are as follows;<br></b>
Accuracy(TP+TN)/(TP+TN+FP+FN) : 0.8833333333333333

Precision(TP/(TP+FP)) : 0.822429906542056

Recall(TP/(TP+FN)) : 0.9777777777777777

F-Measure(2PR/(P+R)) : 0.8934010152284264
