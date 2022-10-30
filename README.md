# We-Rate-Dogs-TWitter-User-Analysis

INTRODUCTION
This is project on data Wrangling , which involves the transformation of raw data to a very clean data for further analysis. Originally most data are gotten in their original state, and in that state , they are dirty, messy and untidy,  hence the need for data wrangling. 
There are three stages in the data wrangling process, this includes the following 
1.	Gathering Data: This involves gathering data from the source. In this project , I used the WeRateDogs tweets from twitter, but the data were gathered in three different ways :
i.	Twitter Archive data: This I downloaded straight from Udacity repository. It was given to them by the owners of the WeRateDogs twitter handle.
ii.	Image Prediction File: This I downloaded pragmatically using the Request library from this [link](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv) to  twitter web page
iii.	Twitter API Data: this I got through the use of twitter Api. In this project I got the Json file  by querying  the twitter Api using the tweepy library to obtain more information as regards to the tweets’ id in the Archive file such as the  retweet counts and favorite counts.

2.	Assessing Data: Here we look at the data to check and remove unwanted parameters, hence assessing them for Quality and Tidiness issues; this could be inconsistencies, completeness or validity issues. we watch out for them and document them so as to aid our cleaning process. There are two as to assess data; either visually looking at the data or using built in functions and codes(programmatically)

3.	Data Cleaning; This is the final stage of the Data wrangling process, it involves removal of unwanted data, it follows three definite stages which includes Defining the issue and what to do about it, secondly, writing  codes for the cleaning process and finally testing the code to make sure it works. This can be done by defining some functions, such as try, exceptions, for loop etc Merging data together using some pandas built-in functions such as the melt, merge, drop, etc, which are some of the functions I used in this project. 

Project Insights  
### 1 *The Most Popular Dog Breed*  
From the cleaned data. I took a look at Ten(10) most popular Dog breeds in the data set. it can be observed that the most popular breed of dogs by value count is Golden Retriever with the value count of 169. Followed by Labrador Retriever with the value count of 106 while the 3rd is the Pembroke  with a value count of 95.   
### 2. *Relationship between Favorite Count and Retweet Count*  
From the scattered plot graph, we can clearly see that the two values are correlated . we have more of the favorite and retweet count at the same region of the graph between 25,000 favorite counts and 10,000. While nothing much is happening at the upper region. This means that there are high chances of people seeing retweeted post than post without retweet. The more you retweet a post the more people see it and they more reactions they are likely to get.
### 3. *Dog Stage with the Favorite count*  
Here we can clearly see from the boxplot  that the most liked(favorite count) dog stage is the Doggo stage followed by the Puppo stage.. This also show that people also keep dogs that are between the Doggo and Puppo dog stages., may be because they are more friendly. We can also notice that there lots of dogs that their stages are not defined from the gragh: this might be as a result of people finding it very difficult to differentiate between Dog Stages

CONCLUSIONS
Data Wrangling process helps in delivering a very clean and tidy data for further analysis and visualization. 
After cleaning the data I save my cleaned data to a CSV file name twitter_master_archive data. It can be shared to anybody that wants to explore the data without any further cleaning	

