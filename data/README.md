## Data files for COMM318 _Stories from data_ Final Project

     
### Within the `raw` folder:   
     
* `OECD_child_wellbeing.csv`__: indicators for child well-being across OECD member and non-member countries.__ 
    This data set was downloaded from the [OECD Stats](https://stats.oecd.org/) database where I chose variables from the section on child well-being. The data includes duplicate columns and columns that are completely empty.
    Used in "Initial_Data_Exploration_(OECD)"
* `online_tutor_geoMap.csv`__: Google Trends data - relative popularity of four search terms from August 1, 2019 to December 18, 2020.__ 
    This data shows the average WEEKLY popularity of a Google search term.
    Used in "Data_Analysis_(Google_Trends)"
* `online_tutor_multiTimeline.csv`__: Google Trends data - state popularity of four search terms from August 1, 2019 to December 18, 2020.__ 
    This data shows the average popularity of a Google search term for the entire time period within each STATE.
    Used in "Data_Analysis_(Google_Trends)"
* `nhes.csv`__: data from the "Parent and Family Involvement" section of the National Household Education Survey (NHES).__
    This is data from national survey of parents with school-aged children. The data contains information about the child's school, academic career, parent involvement in school affairs. Specifically, this data set has information about children who are homeschooled in addition to children who attend public or private schools. This data includes column names that are confusing to read and categorical variables with integers standing in for categories.
    Used in "Initial_Data_Exploration_(NHES)"

### Within the `cleaned` folder:   
* `CLEAN_OECD_child_wellbeing.csv`__: cleaned version of `OECD_child_wellbeing.csv`.__
    The cleaned version of this data has removed duplicate columns and made the column names easier to understand.
    Used in "Data_Analysis_(OECD)"
* `OECD_child_wellbeing_2015.csv`__: subset of `CLEAN_OECD_child_wellbeing.csv`.__
    This data frame filtered `CLEAN_OECD_child_wellbeing.csv` to only use data from the year 2015.
    Used in "Data_Analysis_(OECD)"
* `nhes_CLEAN.csv`__: cleaned version of `nhes.csv`.__
    The cleaned data has columns that have been appropriately renamed and numerical variables that were recoded to categorical variables according to the codebook.
    Used in "Data_Analysis_(NHES)"


### Within the general `data` folder:
* `hmsc_df.csv`__: subset of `nhes_CLEAN.csv`.__
    This data frame filters only for the students in the data who were homeschooled.
    Used in "Data_Analysis_(NHES)"
* `hmsc_df.csv`__: subset of `nhes_CLEAN.csv`.__
    This data frame filters only for the students in the data who were enrolled in public or private schools.
    Used in "Data_Analysis_(NHES)"
