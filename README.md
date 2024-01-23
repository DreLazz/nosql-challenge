# NoSql-challenge

# Summary of Assignment

## In this assignment I was tasked with evaluating various food estblishments across the United Kingdom at the request of the magazine editors from Eat Safe, Love. I was tasked with evaluating the rating data to help the their journalists and food critics decide where to focus for future articles. 

# Methods Used

## In the first part of the assignment I set up a Mongodb database with the name of "uk_food" and a collection with the name of "establishmnets". The first part of the assignment was to use the provided "establishments.json" and import it into jupyter notebook and database for use. Next, I had to see if the file was succesfully imported by confirming the database and it's collection were correct. I then had to add a new restaurant named "Penang Flavors" to the current collection and make updates to the database using "insert_one" and "update_many". In the second part of the assignment I had to analyze the collection for specific requests using queries. I had to find the establishments that had hygine scores equal to 20, establishments with rating values or 4 or greater using queries and pipelines to create a dataframe. 