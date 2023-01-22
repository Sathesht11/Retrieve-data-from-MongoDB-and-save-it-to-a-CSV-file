# Retrieve data from MongoDB and save it to a CSV file
This method is used to retrieve data from a MongoDB collection. First, mongoDB connection was made, then collection.find() query is used to read the data.The data is then transformed into a dataframe using the pandas library. Finally, the dataframe is saved as a csv file in the current working directory.

# Data 
The sample data from MongoDB was used. The database'sample mflix' collection 'users' has been used.
