# Neural_Network_Charity_Analysis
1.	Overview of the analysis:   The purpose of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
2.	Results: 
o	Data Preprocessing
	What variable(s) are considered the target(s) for your model?
	The  variable  that is considered to be the features for your model The IS_SUCCESSFUL column.
	The variables that are  neither targets nor features, and should be removed from the input data are The EIN and NAME columns beeacuse they bring no value to the data.
o	Compiling, Training, and Evaluating the Model
	layer 1 100 neurons with a relu activation. For layer 2, 80 neurons and continued with the relu activation. Then switched to  sigmoid for layers 3 (60 neurons) and layer 4 (20 neurons).
	I was not able to achieve the target model performance I got 0.7173177599906921
	![image](https://user-images.githubusercontent.com/103130997/188341794-482f9262-d529-43fe-af85-08c47c432116.png)
 
	No steps did were taken to try and increase model performance
Summary: The relu and sigmoid activations yielded a 72% accuracy,  next step should be to try the random forest classifier as it is less influenced by outliers.

