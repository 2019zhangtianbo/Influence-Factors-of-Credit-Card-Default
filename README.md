This project focus on determineing the influence factor of credit card default. It's a pretty primitive project for a undergraduate course. Have fun!!

Data:
Two Ways:
1. Downloa the "default of credit card clients.xls" file from the data folder on : 
https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
	1. Manually change the data file from .xls to .csv
	2. Delete the first row of the file (Because it's in the form of x1, x2, etc.)
	3. Remember the path to the file for the program
2. Use the given data set (We did the same process as option 1)
	1. Remember the path to the file for the program


Program:
Look at the boilerplate code(if __name__ == '__main__':), you will find there are two field:
1. data_path: This field should be the path to the data file
2. result_path: This field should be the path to where you would want to store the results
So these two fields should be changed, else the code won't run.


Package:
If you are using ananconda, it's easy to operate just right click on the packages to install them
The packages include:
pandas
seaborn
matplotlib.pyplot
statmodels.api
sklearn

ALL DONE!
