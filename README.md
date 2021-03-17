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
2. General DF functions: df.iterrows(), df.rename(), df.index.astype(), nparray.reshape(), df.value_counts(),
3. Mapping sequence(Series) using lambda: sequence.map(lambda x: x[6:])
5. Working with indexes: df.reset_index(), df.index.get_level_values(), df.reindex(),
6. 
7. Sorting and locatiing : df.loc/iloc, df.sort_values(),  pd.notnull()
8. Groupping, aggregation (split-apply-combine) : df.groupby().agg() or . mean() , .max(), .min().
9. Merging concatinating: pd.concat(), pd.merge,
10. Reshaping: df.pivot_table()
11. 
12. Quick scraping: pd.read_html()
13. Math and data formatting: preprocessing.MinMaxScaler()
14. Visualization : lineplot, barplor, sns.lmplot(), df.plot(),
