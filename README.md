# python-homework

# PyBank Assingment 

### The first intiative is to bring in our data using the csv import.
### Next we want to create a path in order to locate our csv file, once that is done we set the path that contains our file. 

### Prior to reading the data,  I have set variables in place to track and account for items in our data. This is done so that we are able to iterate through the data and make calculations based on these measurments. 

### Next we want to read the data, via the csv reader function and reassign the file to correspond with a diffent name, in this case csvreader. This will permit the the file to be read in a csv format for which it was intended. With the open with command (csv_path, 'r') we open up our path to direct us to where the file is stored then using the command we are able to read the file. 

### Now that we have brough in our data we can start manipulating and wroking with this information. 
### In the following steps we want to convert the data from each column in our list from a string into an integer for functionality. 
### We can assing a variable and covert the string into an integer using the int[row] command, this will account for each value as an integer in the current index. As there are two clomumns to convert into integers we have to assign a variable int function for each as one contains informaton of dates and the other has profit/losses numbers.

### In the following we want to apply our metricts/variables that we have already created in order to calculate our total count and total sum, this allows us to use the answer from each total to come up with 2 new variables that we may use to provide us with more information, this will help us in answering other questions related to the data. 

### The next step is to calculate the revenue change using our converted string integer which is current_revenue and subtracting a varaible stated as prev_revenue, this will give us the revenue change, and in order to cylcle through this we want to make the prev_revenue equal to the curent revenue so we can go down the list of numbers and iterate. This will provide us with a new list that we will call, revenue_change_list, using and iterating through this list will allow us to calculate, the average_change of each row, the greatest increase, and greatest decrease in profit an losses. We can also assign a month_of_change variable to put all of our corresopnding dates into a new list. 

### Now that we have our revenue_change, greatest_increase, and greatest_decrease, we will create an if statement to iterate through our revenue_change_list to determine what was the greatest increase in profits for which day and what was the greatest decrease in profits for that day as well. 

### Lastly we will use our revenue_change_list to find the average reveune change by summing all items in our revenue chnage list and then dividing the number of of total months to get the average reveune change. Now we have our total_revenue, total_months, average_change, the greatest_increase, and greatest_decrease with corresponding dates. 
### This is now ready to be printed for the final results.
