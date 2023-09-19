# PHASE 1 PROJECT

#Project Overview

This project aims to help analyze data from several data sets about movies with the goal to get insights and advise Microsoft technology company that want to venture into movies production. Being new to Microsoft, the project will major on data analysis to get insights

#Business Objective

The main objective is to provide insights to Microsoft and advise on movie creation that will have more profit margins which will increase the companies revenue.

#Data 

Data sources for this project are; Box Office Mojo, IMDB, TheMovieDB, The Numbers.

#Business Success Criteria

The business criteria is;

Revenue growth

Profitability

Factors affecting revenue

#Requirements, Assumptions, and Constraints

Requirements; Dtasets containing all the information needed

Assumptions; The provided information is true

#Data Understanding

There is one merged dataset from 3 datasets and it provides information about different movies. It contains the columns below.

'tconst': This is the  unique identifier for each movie.

'averagerating': This column represents the average rating of the movie.

'numvotes': This column indicates the number of votes the movie has received.

'primary_title': This column contains the primary title of the movie.

'original_title': This column contains the original title of the movie.

'year': This column represents the year when the movie was released.

'runtime_minutes': This column indicates the duration of the movie in minutes.

'genres': This column contains information about the genre(s) of the movie.

'title': This column contains another title of the movie.

'studio': This column represents the movie studio associated with the movie.

'domestic_gross': This column indicates the domestic gross for the movies.

'foreign_gross': This column represents the foreign gross earnings for the movie.

'total_gross': This column represents the total gross earnings, and its both domestic and foreign earnings.

'first_word': This column contains the genre types.

#Data Preparation

The datasets were in form of CSV, loaded them using the right libraries for preparation and checked the data

Cleaned the data to remove duplicates, columns and missing values

#Data Analysis

Analysis was done to help answer business success criteria; to make more profit and also help in growth revenue.

Factors Affecting Revenue 

a. Foreign gross and Domestic grosss

From this plot we see that every year foreign gross is higher compared to domestic gross. 

2017 was the best year in terms of foreign gross and total made was 1.964745e+14, while 2016  was the best year in terms of domestic gross with 9.681405e+13.

![image](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/141718217/0803e938-0e7a-40d8-9da0-0179062edde9)

b. Total gross and Year

From this plot we see total gross has been on increasing trend over the years until 2018 where a big drop was experienced compaared to 2017 

![image](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/141718217/fa1a5274-76a8-40d7-837a-d4ae8cbf422a)

c. Count of Genres and Year

From this plot we see number of genres being produve year over year have been on increasing trend until 2017 and 2018 where count dropped to 2660504 and 2108232 from 3531330 in 2016.

This explains why gross also had a drop in 2018

![image](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/141718217/9739630b-8627-4131-b8c9-427ac92ce9b7)

d. Genre and Gross

Game -Show genre has the highest gross with gross of 5.469383e+07

![image](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/141718217/f02e1395-0f00-4723-8362-f8b3e05badb5)


#Conclusion

In coclusion, data analysis has provided valuable insights from the datasets providing information to help in business starategies. 

Throghoutthe project I have been able read, prepare, clean and analyze data and can help address some decisions.

#Recommendations

1. Microsoft to focus more on foreign sales than domestic sales. Foreign sales are more with highest sales recorded in a year at 1.964745e+14 while domestic gross was at 9.681405e+13.

2. For the copmany to make more money year on year, more movies need to be produced in subsequent years. In the year 2017 and 2018, 2660504 and 2108232 a drop from previous years. This lead to a deacrease in gross sales in 2018 which had a gross sales of 8.277638e+13 in foreign sales and 1.451599e+14 in domestic sales.

3. Focus to be more in producing movie genre of Game-Show. They have the highest foreign gross of 5.469383e+07 and also have the highest ratings and are rated 9.000000 out of 10.
