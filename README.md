# Data-Extraction-and-Analysis-with-Pandas

# Tools Used
* Pandas 
    * for reading csv file
    * storing information in dataframes
* Jupyter Notebook
    * visualizing dataframes
    * checking outputs for calculations
    
    
# Overview
## Heroes Of Pymoli Observations
## Direct comparison of player gender breakdown before and after dropping duplicate entries:
As we can see, dropping duplicates from the original dataframe reduced the number of male players by 168 (from 652 down theo 484), reduced the number of female players by 32 (from 113 down to 81), and reduced the number of undisclosed genders by 4 (down from 15 to 11).

With such a small difference in total overall numbers, the gender breakdown changed minimally, from 83.59% to 84.02% for males, from 14.49% to 14.06% for females, and from 1.92% to 1.91% for undisclosed/other.

Since the overall percentage for the gender breakdown didn't change much regardless of whether or not we kept the duplicate players in the dataframe, dropping the duplicates in _this specific_ case wasn't necessary. However, this was a good practice in checking how the results varied depending on how we analyzed the data, and an indication that **the results of any data analysis is contingent on how the data is interpreted**.
![gender df](Images/totalPlayersGender.jpg "Gender Breakdown before dropping duplicate player entries")
![unique_gender df](Images/uniquePlayersGender.jpg "Gender Breakdown after dropping duplicate player entries")

--------
## Analysis

* Of the 780 active players, the vast majority are male (~84%). There also exists, a smaller, but notable proportion of female players (~14%).
* Our peak age demographic falls between 20-24 (46.79%) with secondary groups falling between 15-19 (17.44%) and 25-29 (12.95%). 
* Of the 780 purchases made, there were 183 unique items that sold for an average price of $\$$ 3.052 for a total revenue of $\$$ 2379.77


* Breaking down the purchases
   * by gender showed:
       * That 113 of the 780 purchases were made by females for an average price of $\$$ 3.20 for a total of $\$$ 361.94
       * That 652 of the 780 purchasese were made by males for an average price of $\$$ 3.02 for a total of $\$$ 1967.64
       * That 15 of the 780 purchasese were made by someone with other/non-disclosed gender for an average price of $\$$ 3.35 for a total of $\$$ 50.19
   * by age showed:
       * The 20-24 age group purchased the most items,	365 out of the 780 total purchases, for an average price of $\$$ 3.05, creating a total revenue of $\$$ 1,114.06.
       * The 15-19 age group purchased the second most items, 136 out of the 780 total purchases, for an average price of $\$$ 3.04, creating a total revenue of $\$$ 412.89.
       * The 25-29 age group purchased the third most items, 101 out of the 780 total purchases, for an average price of $\$$ 2.90, creating a total revenue of $\$$ 293.00.
        
        
* The top spenders:
   * The top spender was Lisosia93, making 5 purchases at an average of $\$$ 3.79 and generating a total of $\$$ 18.96.
   * Idastidru52 spent the next most money, making 4 purchases at an average of $\$$ 3.86 and generating a total of $\$$ 15.45.
   * Chamjask73 spent the third most amount amount of money, making 3 purchases at an average of $\$$4.61 and generating a total of $\$$ 13.83.


* The most popular item was by far Oathbreaker, Last Hope of the Breaking Storm, which sold 12 units. Following Oathbreaker, there was a 3-way tie for second place between Fiery Glass Crusader; Extraction, Quickblade Of Trembling Hands; and Nirvana, with each selling 9 units each.

* The most profitable item was Oathbreaker, Last Hope of the Breaking Storm, which brought in $\$$ 50.76, followed by Nirvana with $\$$ 44.10, and Fiery Glass Crusader with $\$$ 41.22.

----- 
