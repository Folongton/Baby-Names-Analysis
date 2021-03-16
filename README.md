# Baby-Names-Analysis
Analysis of Baby names from SSA data for the past 110 years.

*To save time navigating, please refer to the below contents and list of tools.*
### Structure of analysis and tools used:

##### Python packages used : 
1. Pandas, Numpy, Openpyxl (for analysis and data manipulation)
3. os, time (for reading files and timing some functions)
4. seaborn and pyplotlib (for plotting)
5. SequenceMatcher class from difflib (to match names to misspelled and alternatively spelled names)
6. preprocessing module from sklearn (to normilize some data before plotting)


##### Methods and technics, related to data analysis, used:
1. pd.read_csv()
2. df.iterrows()
3. Working with indexes: df.reset_index()
4. Sorting and locatiing : df.loc/iloc, df.sort_values()
5. Groupping, aggregation (split-apply-combine) : df.groupby().agg() or . mean() , .max(), .min()
6. Merging concatinating: pd.concat(), pd.merge
