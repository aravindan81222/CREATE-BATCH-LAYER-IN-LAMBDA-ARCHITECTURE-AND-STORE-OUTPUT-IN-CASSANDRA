# CREATE-BATCH-LAYER-IN-LAMBDA-ARCHITECTURE-AND-STORE-OUTPUT-IN-CASSANDRA
INTRODUCTION: 
Our task is to prepare batch layer of lambda architecture. We have to do some basic analytics and display the output as well as transfer the output into Cassandra tables.   

TASK: 

1.Show number of downloads for package ggplot2 

2.Highest number of downloads by a country and Operating System. 

3.Top 10 (distinct) largest sized packages 

4.What are the top 10 most popular (distinct) packages? 

5.In both days, at what specific hour there are most of the download hits? 

6.What are the 5 most popular packages in UK? 

7.Show total number of downloads by (each of the) top five machines? 

8.Show top three OSs that are most popular among the R programmers?

9.Show total number of downloads by each OS type? 

10.Show total number of downloads by each country?  

CONCLUSION: 
Thus, the key space having ten tables which fetched the values from spark sql. All the information and values are successfully loaded into Cassandra tables. 
