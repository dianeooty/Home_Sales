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
![Example screenshot](./img/screenshot.png)
<!-- If you have screenshots you'd like to share, include them here. -->


## Setup
Load Home_Sales.ipynb to Google Colab and run the codes.


## Project Status
Project is complete and no longer being worked on.


## Acknowledgements
- Many thanks to the instructional team and David Chao.


## Contact
Created by Diane Guzman
