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
1. Reading / writing: datapd.read_csv()
2. General DF functions: df.iterrows(), df.rename(), df.index.astype()
3. Mapping sequence(Series) using lambda: sequence.map(lambda x: x[6:])
4. Working with indexes: df.reset_index()
5. Sorting and locatiing : df.loc/iloc, df.sort_values()
6. Groupping, aggregation (split-apply-combine) : df.groupby().agg() or . mean() , .max(), .min().
7. Merging concatinating: pd.concat(), pd.merge,
8. Quick scraping: pd.read_html()
9. Visualization : df.plot(),
