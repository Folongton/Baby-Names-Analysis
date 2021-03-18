# Exploratory-Baby-Names-Analysis
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
1. Reading / writing: datapd.read_csv(), df.to_excel(),
2. General DF functions: df.iterrows(), df.rename(), df.Series.astype(), nparray.reshape(), df.value_counts(), np.sum(), df.columns, df.drop(), df.assign(),
3. Mapping sequence(Series) using lambda: sequence.map(lambda x: x[6:])
5. Working with indexes: df.reset_index(), df.index.get_level_values(), df.reindex(), df.index.name, pd.MultiIndex.from_tuples()
7. Sorting and locatiing : df.loc/iloc, df.sort_values(),  pd.notnull(), df.at[], 
8. 
9. Groupping, aggregation (split-apply-combine) : df.groupby().agg() or . mean() , .max(), .min()., .nlargest()
10. Iteration over gropped object: for key1, group1 in groupped1: ,
11. Merging concatinating: pd.concat(), pd.merge(),
12. Reshaping: df.pivot_table(), df.T, df.melt(), 
13. 
14. Quick scraping: pd.read_html()
15. Data formatting and miscellaneous: preprocessing.MinMaxScaler(), SequenceMatcher(), Series.tolist(), Moving Average of series - Series.ewm(),
16. Visualization ( and preparation for it) : lineplot, barplor, sns.lmplot(), df.plot(),

#### Structure of analysis:
1. Import all packages, module, classes needed and setting some basic settings.
2. Reading data from 51 files separated by state.
3. The most used name in a single year over all states.
4. The most used name for each state for all years.
5. Total US population by year.
6. Total births by sex and year.
7. Normalization before plotting.
8. 10 most used names in all 110 years by sex.
9. Unique names for male and female.
10. The most used name each year by sex.
11. How many years each top name was on a top.
12. Top name for each year.
13. Number of distinct names over years.
14. Longest and Shortest names.
15. Impact of alternative spelling.
16.  Use of ethnic names over the years.
