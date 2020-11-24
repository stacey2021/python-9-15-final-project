Python-9-15 Final Project

Introduction
My project would review Museum of Modern Art(MoMa) artwork collections data. Two datasets have been pulled directly from this website: https://www.kaggle.com/momanyc/museum-collection. The first dataset contains basic information for each artwork, includes artwork title, related artist id & name, department, etc. The second dataset contains artist information, includes artist id, name, nationality, gender, etc. I would like to group the artwork collection data by department, by acquisition date and by the related artist gender & artist nationality.

Libraries
I used below libraries: Pandas, Matplotlib Plotly, Seaborn

Data Import & Clean
Import two csv files using Pandas read_csv.
Clean the Gender column in artists dataframe and clean the Date column in artworks dataframe.
Rename columns in these two dataframes and change the data types before merge two dataframes.

Data Join
Merge two datasets into one that shows artwork by the artwork information and related artist information.

