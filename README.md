![Microsoft](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.microsoft.com%2Fen-us%2Flegal%2Fintellectualproperty%2Ftrademarks&psig=AOvVaw2JmLMbLnSUqyoQ7BjoM3VN&ust=1711175946704000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCLjl7aihh4UDFQAAAAAdAAAAABAE)
# WHY MICROSOFT SHOULD INVEST INTO THE MOVIE INDUSTRY

The following data set and analysis is used to get actionable insight into this industry to create a profitable and revenue-generating
movie production for Microsoft by Microsoft.

## Finding
    
~ Quality in movie production(higher production budget) creates grounds for good profits from the global market.
~ Standout genres having a higher rating are Animation, Drama, History, Sports, Biography
  while lower rated genres include horrors etc
~ Higher budget movies tend to bring out good ratings hence good customer satisfaction as the margin of the budgets helps the team to concentrate on the detail during movie production

## Data Analysis

From the datasets provided, I used the following datasets provided in our repository:

    * bom.movie_gross_csv.gz
    * tn.movie_budgets.csv.gz
    * im.db(sql database)

With this data, my approach for the analysis below was to get 
an understanding on the relationships between the budget for production,
how much income it would regulate associated with their ratings and the genres 
involved as well

## Notebook

I used Visual studio code to analyze our data and code analysis and in the first block we 
went ahead to import the necessary libraries,connecting to our sql database(im.db) 
and extracting the data from the different datasets provided.
* Printed the datasets to ensure it was extracted properly
* Merged the corresponding data sets to create one database for easier and concise coding
* Renamed the corresponding columns to match each other so as to merge the tables(columns)
* Cleaned the datasets to be used to prevent any anomalies while interpreting the Data 
as well as to reduce the chances of errors appearing in our code.

I ventured into three arguments for our data analysis;
* Average Rating vs Budget Analysis
* Average Rating vs Genre Analysis
* Production Budget vs Worldwide Gross

### Average Rating vs Budget Analysis

The average rating column was referenced to our budget analysis and the findings we got was that 
generally an upward trend was noticed in the rating as our budget increased

![Average Rating vs Budget]("C:\Users\amutu\Downloads\output.png")

### Average Rating vs Genre Analysis

The average rating column was again cross referenced to our genre column to try and 
find the most popular genres among our viewers.
he genres are fairly aligned although it doesn't present a strong case for causation. But from the data we can also tell that there is correlation between certain genres and the higher the ratings and this can help us decide on which avenue we would like to venture
into.

![Average Rating vs Genre]("C:\Users\amutu\Downloads\output3.png"))

### Production Budget vs Worldwide Gross

Finally not forgetting the finances involved, I decided to check the trend of these movies
and how investing into quality would correspond to the global market in terms of revenue generating
From this we can tell that putting the work during creation and production would generally 
appease the global market so might be something worthwhile to think about.

![Budget vs Worldwide Gross]("C:\Users\amutu\Downloads\output2.png")

## Conclusion

From our conclusive findings; 
* I would recommend investing well in the production budget
so as to increase our chances of appeasing the market and this would in turn generate revenue
* Also venturing into the popular genres as stated earlier would make the movie popular amongst
our viewers bringing as back to revenue generated!
* Also investing in our budget would generally bring a higher rating

From my findings, I heavily concentrated on the financial aspect to try and bring out a clearer picture
and give better insights to the company to be able to plan themselves well and reduce
the risk of loss.

Gracias!!