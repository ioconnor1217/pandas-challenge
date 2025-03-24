# pandas-challenge
In this challenge, I used a jupyter notebook file, read two seperate csv files, convert them into dataframes, merge both of those dataframes togethter, output several different charts for quick ananlysis, and gave written description of two observable trends.

### About the code
I declared some formatting functions in the beginning for readability. However, this caused some problems later on in the code. I was having to re-declare variables before performing calculations for the output of a different chart. To fix this, I just created a copy of the unformatted dataframe to perform the calculations on.

### Citations
- I used [this](https://pandas.pydata.org/docs/reference/general_functions.html) to create my formatting functions.
- I used [this](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html) to check why my dataframes were not working. 
- I used [this](https://pandas.pydata.org/docs/reference/api/pandas.cut.html) to get more help with pd.cut.
- I used [this](https://github.com/jupyter/notebook/issues/1080) to figure out why dollar signs were messing up my markdown file. 
