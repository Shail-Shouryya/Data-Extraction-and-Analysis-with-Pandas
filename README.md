# Heroes-of-Pymolli
## Overview
### Heroes Of Pymoli Observations
* Of the 1163 active players, the vast majority are male (84%). There also exists, a smaller, but notable proportion of female players (14%).
* Our peak age demographic falls between 20-24 (44.8%) with secondary groups falling between 15-19 (18.60%) and 25-29 (13.4%).  
#### Direct comparison of player gender breakdown before and after dropping duplicate entries:
As we can see, dropping duplicates from the original dataframe reduced the number of male players by 168 (from 652 down theo 484), reduced the number of female players by 32 (from 113 down to 81), and reduced the number of undisclosed genders by 4 (down from 15 to 11).

With such a small difference in total overall numbers, the gender breakdown changed minimally, from 83.59% to 84.02% for males, from 14.49% to 14.06% for females, and from 1.92% to 1.91% for undisclosed/other.

Since the overall percentage for the gender breakdown didn't change much regardless of whether or not we kept the duplicate players in the dataframe, dropping the duplicates in _this specific_ case wasn't necessary. However, this was a good practice in checking how the results varied depending on how we analyzed the data, and an indication that the results of any data analysis is contingent on how the data is interpreted.
![gender df](Images/totalPlayersGender.jpg "Gender Breakdown before dropping duplicate player entries")
![unique_gender df](Images/uniquePlayersGender.jpg "Gender Breakdown after dropping duplicate player entries")

## Tools Used
* Pandas 
    * for reading csv file
    * storing information in dataframes
* Jupyter Notebook
    * visualizing dataframes
    * checking outputs for calculations
