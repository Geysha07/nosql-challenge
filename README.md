# Module 12 Challenge: Eat Safe, Love
For this challenge, we used MongoDB to evaluate data from food establishments across the United Kingdom. 
We imported our dependencies, started an instance of MongoClient, assigned our database and collection name to variables and started our analysis.

In the first part of the challenge, we added a new restaurant to our collection using "insert_one". After this, we performed a query to find the BusinessType ID for "Restaurant/Cafe/Canteen" and then updated our new restaurant with the ID we found. Then, we used "update_many" to convert latitude and longitude to decimal numbers and RatingValue to integers. 

The second part of our challenge was to conduct exploratory analysis on our data in order to answer the following questions.

1. Which establishments have a hygiene score equal to 20?

2. Which establishments in London have a RatingValue greater than or equal to 4?

3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
