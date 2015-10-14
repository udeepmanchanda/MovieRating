Movie Rating - Big Data Analytics
======================
+ Author: Udeep Manchanda.

#### Description
-----------
Implement several map reduce design patterns to derive some statistics from IMDB movie data using Hadoop framework. 

#### Dataset
+ movies.dat MovieID::Title::Genres
+ users.dat UserID::Gender::Age::Occupation::Zip-code
+ ratings.dat UserID::MovieID::Rating::Timestamp

#### Map Reduce Design
+ Given a input zipcode, find all the user-ids that belongs to that zipcode. You must take the input zipcode in command line.
+ Find top 10 average rated movies with descending order of rating.
+ Find all the user ids who has rated at least n movies.
+ Given some movie titles in csv format - find all the genres of the movies.
+ Find the top 10 zipcodes based on the average age of users belong to that zipcode, in the ascending order of the average age.
