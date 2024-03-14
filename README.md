# Close_the_door
forex_try is aimed at identifying income among the customer database. 
To debug the program, I created a test transaction history of 100 clients based on the trades of free trading robots in Metatrader 5.

Main Menu:
Download data - download .csv file with transaction history. 
Show data - creates a window with a data table to view 
Select features - opens a window for selecting features that are involved in training the model. Decryption in the same window; 
Describe stat- was previously created to reflect a brief summary of the downloaded data. At the time of publication, this item does not work. 
Predict for one date - opens a window with a field for entering the date at which the analysis will be performed. (for a week, a month ahead, all of them). After processing the data, a list with success percentages for a particular period will be displayed above the button. 
Predict for custom period - creates an analysis as in the Predict for one date button, but for the period specified by the user. By clicking the results button, it displays a table of the results of the evaluation of the run and a graph with these values. 
Current predict - creating the current forecast. The last date that was in the downloaded data is used as the date of analysis. Then the model is trained and forms a further forecast. The results of the above forecast will be saved in the file directory.
