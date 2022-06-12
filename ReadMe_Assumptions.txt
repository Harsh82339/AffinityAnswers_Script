Assumptions 

1 - We Are given an Excel file (xlsx format) Filename = realdonaldtrump.xlsx
2 - The Excel Sheet contains tweets made by Donald Trump.
3 - The Columns are as follows ['Id','link','content','date','retweets','favorites','mentions','hashtags']
4 - We Search for the Keywords/ words that indicates racial slurs in Column 3[content]
5 - The Keywords considered are ['facebook','youtube'] 
6 - We Return the Tweet Id and Keyword used in that tweet. 

Python libraries Required 
1 - Pandas
2 - openpyxl
