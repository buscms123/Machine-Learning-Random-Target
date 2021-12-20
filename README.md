# Machine-Learning-Random-Target

------------------------------------------------------------------------------ 
------------------------------------------------------------------------------ 
 Machine Learning Predictive Modeling Competition. 
------------------------------------------------------------------------------ 
------------------------------------------------------------------------------ 
----- 
Goal:  
----- 
There are THREE targets to predict using the given attributes v1--v127 as input variables. YOU  MAY CHOOSE TO MODEL ONE OR ALL OF THESE TARGET VARIABLES. You are only required to  pick one to work on, but you are welcome to attempt 2 or all 3. 
1. cont.target -- This is a continuous target variable 
2. binary.target1 — This is a binary target 
3. binary.target2 - Also a binary target 
For the 2 binary targets, false positives are more costly than false negatives - certainty regarding predicted events is paramount and thus the accuracy of the model might best be  scored using positive predictive value or lift at depth of 10-20%. Area under the ROC curve and  Averaged Squared Error are also sound and common error metrics used in this application. 
binary.target1 and binary.target2 are not mutually exclusive events. Each row could have  neither event, both events, or one of the events. The two targets are related in some sense and  researchers would be interested in anything that might inform them that one event might be  more likely to happen than the other. So far the approach to that problem is to build two  models and use the output from both models to decide which event is more likely to happen.  
------------------- 
THREE Deliverables: 
------------------- 
1.) Submission of predictions following the convention in the sampleSubmission file. The (up to)  4 column names on this file should be "row", “cont.target”, “binary.target1”, and/or  “binary.target2” (NOT capitalized) and contain the predictions for the rows of the test data in  the order they are found in the test data. The name of this submission file should be  "CohortColorTeamNumber.csv" For instance, if you are on Blue team 6, the name of the  submission file should be "Blue6.csv". The color should be capitalized. To calculate the final test MAE to  determine a winner. I need the naming convention to make that job easier.  
2.) A brief write up that describes your modeling process. 
3.) A zip file that contains your commented code or a note within your report that indicates the  name of your project.
