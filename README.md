# deep_learning_Challenge


NEURAL NETWORK MODEL REPORT

__________________________________________________________________

The purpose of this analysis is to create a machine learning tool for Alphabet Soup, a non-profit foundation, to identify applicants with a high chance of funding success. A CSV file containing data from 34,000 organizations was evaluated and preprocessed. This preprocessing included identifying target and feature variables, dropping unwanted columns, binning, and encoding categorical variables using the 'get_dummies' function in pandas. The data was then split into training and testing datasets, and both sets were scaled. Sequential modeling was performed using TensorFlow and Keras on the training datasets.


The target variable for the model is the 'is_successful' column, while the feature variables include all columns except 'is_successful,' which is used to train the model for predicting the target variable. The 'EIN' and 'NAME' columns were dropped from the DataFrame as they are not considered target or feature variables. The hidden layer units used for the model are shown below.



<img width="665" alt="Screenshot 2023-09-10 at 3 17 33 PM" src="https://github.com/Ayan2127/deep_learning_Challenge/assets/126814705/f7986199-1afb-4dfa-a9bc-e8277b255ee4">


Although the current model does not meet the target model performance (75%+), it still achieves an accuracy rate of ~73%, which should be sufficient for Alphabet Soup to derive meaningful insights into applicant funding and organizational success. To further improve model performance, steps can be taken, such as creating relevant features that can boost accuracy scores and using regularization tools to prevent overfitting. 


<img width="665" alt="Screenshot 2023-09-10 at 8 53 29 PM" src="https://github.com/Ayan2127/deep_learning_Challenge/assets/126814705/90c6e7f9-4966-47b3-87a8-f7404af27e12">


Recommended experimentation of model variation to enhance its performance, including exploring different model architectures and hyperparameter tuning. Overall, the results of the model can be improved by adjusting hidden units by using small and large numbers and removing less relevant features to reduce noise and potential outliers. 



