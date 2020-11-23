# Blight-ticket-compliance-modelling-using-machine-learning

The files couldn't be uploaded due to heavy size of the datasets

This was the final assignment given by University of Michigan's course on Applied Machine Learning in Python


The assignment had addresses of the ticket holders along with their latitude and longitudinal positions. The addresses were merged with the geo locations and then the address column was removed in the train-test data sets as string are of no use to us.

Then using the LabelEncoder function the relevant data was labelled with respective numbers.
Since the datasets contained several bad data like features with zero correlation or null data, I removed all the null data as well as the data which didn't show much correlation with other features using the .corr() function and plotting its heatmap.

Then Naive Bayes regressor was used to get the base score. We are supposed to perform better than the base score.

Then an appropriate regressor is selected and the answer displayed.
