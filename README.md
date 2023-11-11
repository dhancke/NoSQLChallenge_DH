# NoSQLChallenge_DH

Instructions

NOTE: I HAD ISSUES REINSTALLING MONGODB TO FINISH THIS AND CHECK MY CODE WHICH I HAD WRITTEN A WHILE AGO.

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. The activity involves evaluating ratings data in order to help Food magazine Eat Safe, Love journalists and food critics decide where to focus future articles.

Part 1: Involved setting up the Database and Jupyter Notebook
Requirements:
List the databases you have in MongoDB. Confirm that uk_food is listed.
List the collection(s) in the database to ensure that establishments is there.
Find and display one document in the establishments collection using find_one and display with pprint.
Assign the establishments collection to a variable to prepare the collection for use.

Part 2: Updating the Database
Requirements:
- Adding a new halal restaurant to the database
- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
- Removing andy of the data within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted was required, as they were not interested in those fields.
- Some of the number values are stored as strings, when they should be stored as numbers and needed remediation.

Part 3: Exploratory Analysis
The following questions required answering based on exploring the database:
- Use count_documents to display the number of documents contained in the result.
- Display the first document in the results using pprint.
- Convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows.
- Which establishments have a hygiene score equal to 20?
- Which establishments in London have a RatingValue greater than or equal to 4?
- What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
- The first 5 rows of the resulting DataFrame should look something like this:

_id	count
0	Thanet	1130
1	Greenwich	882
2	Maidstone	713
3	Newham	711
4	Swale	686

