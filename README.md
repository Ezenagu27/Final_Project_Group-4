**Warning running the code can take signficant amount of memory to run because of the large dataset.

The Goal of this project was to take a real data set(Instacart) and to use machine learning (unsupervised) to do customer segmentation.  
In addition, to be able to make meaningful data analysis on the customer segmentation that would benefit the company. 

Data for this project came from. This Dataset was a Competition to predict which item would be added to the cart next, but we repurposed the data into customer segmentation. 

Any new user will have to agree to the terms and conditions of the contest, before they are able to download the files.   The website below has a download all button on the bottom right of the screen.
https://www.kaggle.com/competitions/instacart-market-basket-analysis/data

The majority of the code came from looking at activites from Week 19.   

The code to make the pivot tables came from 
https://pandas.pydata.org/docs/reference/api/pandas.pivot_table.html

The code to normalize the row came from overstack
https://stackoverflow.com/questions/18594469/normalizing-pandas-dataframe-rows-by-their-sums

The code to round the describe function came from 
https://stackoverflow.com/questions/72862898/round-df-describe-results

department_clean_up folder has pictures of the code showing the value counts in specific departments
This was used to clean up the department dataframe earlier in the code and than to rerun the pivot table.
After the department dataframe was cleaned up these codes would have no values because those column values no longer existed and why it was added as pictures
