## Data analysis notebooks for COMM318 _Stories from data_ Final Project

* Note: The notebooks are linked in the date of each entry.

### [10/25/20](https://commjhub.asc.upenn.edu/user/aheyward/notebooks/comm318_F20/comm318_F20_Final_Project/data_analysis/Initial_Data_Exploration_(OECD).ipynb) - `Initial_Data_Exploration_(OECD)`:
This notebook does some early cleaning of a data frame with indicators for child well-being in OECD member nations and those same indicators for some nations who are not in the OECD. This notebook also gives a general look at the distribution of some of the variables. The data was pulled for the [OECD's database](https://stats.oecd.org/) underneath the section on "Social Protection and Well-Being" which also includes data on poverty/wealth distribution, gender, and general well-being. I wanted any data I used to be recent and I wanted to do some temporal analysis, so I chose data from 2014 to 2018 to explore. These explorations include: 
* How many observations and variables are there?
* How many data values are there for each year in the 5-year period?
* How many data values are there for each indicator of child-well-being?
* For each country in the data set, which year provides the most data values? 
* For each indicator, how many values are there per year?
Charts and bar charts help aid visualization of the data's distribution.

### [11/13/20](https://commjhub.asc.upenn.edu/user/aheyward/notebooks/comm318_F20/comm318_F20_Final_Project/data_analysis/Data_Analysis_(OECD).ipynb) - `Data_Analysis_(OECD)`:
In this notebook, I analyze only the OECD data from 2015. Then I create separate data frames for OECD and non_OECD nations. Lastly, I attempt some statistical analysis to answer the following questions:
* Which OECD country has the highest percentage of parental involvement?
* How do standardized test scores compare between OECD and non-OECD countries?
* What percentage of countries have a majority of students who wish to pursue higher education?
* Are children with more involved parents more academically driven?
* Do children with more involved parents perform better in standardized testing? (And other questions about associations)
Visualizations (linear regression plots and bar charts) are included.


### [12/11/20](https://commjhub.asc.upenn.edu/user/aheyward/notebooks/comm318_F20/comm318_F20_Final_Project/data_analysis/Data_Analysis_(Google_Trends).ipynb) - `Data_Analysis_(Google Trends)`:
This notebook examines search trends for educational resources during lockdowns. Parents may have searched these topics to find help for their students studying from home due to COVID-19. I pulled the Google Trends data or four search terms: 'online tutoring', 'online public school', 'learning pod', and 'how to homeschool.' I chose to use data from the beginning of the Fall 2019 semester to the end of the 2020 Fall semester to better visualize search differences during a completely normal school term and the abnormal ones. I answer the following question in this notebook:
* In which week was a certain search term most popular?
* In which state was a certain search term most or least popular?
Line graphs of average weekely and average monthly search popularity are included.


### [12/14/20](https://commjhub.asc.upenn.edu/user/aheyward/notebooks/comm318_F20/comm318_F20_Final_Project/data_analysis/Initial_Data_Exploration_(NHES).ipynb) - `Initial_Data_Exploration_(NHES)`:
This notebook makes basic observations about the 2016 National Household Education Survey. This data comes from the "Parent and Family Involvement" section of the survey. The survey asked for information about the child's school, academic career, parent involvement in school affairs. Specifically, this data set has information about children who are homeschooled in addition to children who attend public or private schools. This notebook mostly does a lot of cleaning, changing column names and recoding variables into categorical data with `string` text. The notebook also answers:
* How many parents participated in the survey?
* How many children in the data are enrolled in public or private school?
* How many children in the data are homeschooled?


### [12/15/20](https://commjhub.asc.upenn.edu/user/aheyward/notebooks/comm318_F20/comm318_F20_Final_Project/data_analysis/Data_Analysis_(NHES).ipynb) - `Data_Analysis_(NHES)`:
In this notebook, I primarily explore data concerning homeschooling in the United States using the NHES data. Because the google trends data showed a marked increase in searches for 'how to homeschool' it is important to explore trends in homeschooling practices. I will answer the following questions:
* What is the average amount of time parents spend homeschooling?
* Do parents enlist outside instructors to teach their kids?
* Do parents/family typically train to become homeschool teachers?
* What is the most popular teaching style?
There are also some liner regression models about associations with parental involvement in children who are enrolled in physical schools.
Bar charts are included for certain questions.