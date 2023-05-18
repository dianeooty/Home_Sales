# Home_Sales
Using SparkSQL to determine key metrics of the home sales data with table views, partitions and caching.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
From the home sales data, I created a Spark DataFrame and then to a temparary DataFrame where we can apply SQL queries to answer the questions.  Next, I cached the DataFrame to check the speed the query result.  We can see that query result returns faster than the original query using the memory process when caching.  We then test the speed with partitioned data. In this case, the partitioned data was not as quick as the original or cached DataFrame.


## Technologies Used
- Google Colab
- PySpark
- SQL


## Screenshots
![1](https://github.com/dianeooty/Home_Sales/assets/117790100/67c1b89d-e042-4a80-ae31-dbb1a8c01e48)

![2](https://github.com/dianeooty/Home_Sales/assets/117790100/f4e2e241-4351-47ad-aec7-becc5d132be6)

![1](https://github.com/dianeooty/Home_Sales/assets/117790100/5d45ec87-78c6-452c-93b0-49b583df1921)

![2](https://github.com/dianeooty/Home_Sales/assets/117790100/109af80e-ce65-4db6-8594-e81579761571)

![3](https://github.com/dianeooty/Home_Sales/assets/117790100/d2b814fe-bde3-4c6d-9297-dc92acdbcd80)



## Setup
Load Home_Sales.ipynb to Google Colab and run the codes.


## Project Status
Project is complete and no longer being worked on.


## Acknowledgements
- Many thanks to the instructional team and David Chao.


## Contact
Created by Diane Guzman
