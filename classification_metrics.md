
Create presentation for teaching a class metrics of classification by the way of learn by inventing
The square brackets contain the content ,after polishing, to be shown.:

- [Here is are two arrays one containing actual and other predicted labels of binary classification: ]
-  Generate two example arrays of lenth 10 having 0x and 1s and also explain what is confusion metrics
- Ask user to prepare confusion metrics. Let them do it by hand.
- Now ask user to create a function to generate the confusion metrics. Provide the function signature in details
- Now, explain other metrics such as precision, recall, F1 score, TPR, FPR etc and their significance
- Ask user to calculate these by hand given the confusion metrics
- Now, ask user to create functions for each of these mtrics to calculate these given confusion metrics. Provide the signature.
- Now, provide users with the outputs of a model (an array of decimal numbers) and ask user to write a function that converts these outputs into 0 or 1 given a thresold. 
- [Question is how to decide on this thresold?]
- [for each thresold value calculate precision]
- [Pick the thresold that gives you the best precision]
- [for each thresold value calculate recall]
- [Pick the thresold that gives you the best recall]
- [for each thresold value calculate F1 Score]
- [Pick the thresold that gives you the best F1 Score]
- Guide user to plot Precision, recall, F1 Score vs Thresold
- Provide the user with the code of training logistic regression on iris dataset and preparing the outcome and then let them use their ploting function of previous step
- Now, guide user to prepare TPR/FPR (ROC) and plot it.
- Now, ask user to write a function that approximately calculate the area of it. Then, explain the signification of AUC ROC curve. 
- For IRIS Dataset, provide him the code to train and generate output using two models. Then, let them find the AUC ROC for both outcomes. And let them understand which model is better.


---
Add slides to teach how to compute area under the curve by the way of Learn By Inventing at the right place.

First ask question to find the area under the line connecting two points [(5, 6), (7, 10)]. Show the diagram with shaded area.

On next(), show the calculation and then answer.

Then provide three points and show the diagram. Let the user calculate the area. on next show the calculation and answer.

Ask user to write the code to compute the area given x values and y values. Provide the function definition and test cases.
