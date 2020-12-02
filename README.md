# Data-and-Results-Visualization-Project

GitHub repository for the Data and Results Visualization course project @ Politecnico di Milano. The goal of the course was to provide the principles and rules of Data Analysis and Visualization.

# The impact of COVID-19 on music streaming

Our project studies the impact of COVID-19 on the music industry with particular focus on music streamings. We gathered our data using the Spotify API and the Spotify top 200 weekly. We also used the iTunes API to retrieve genre information for each song.


## Repository Structure

Our repository contains 3 different notebooks + data folders.

### Data Folders

Data folder are organized in **nation** and **nation_features**, for example 'it' which stands for Italy and **it_features**. The first type of folders contain the plain top 200 weekly chart of the mentioned nation, spanning from the first available data (which is different for every nation) until August 2020. 

The second type of folders contain the top 200 weekly with features, such as *Danceability*, *Energy* ecc... These features have been retrieved using **Spotify API**. Music genres have been collected using **iTunes API**. 

**NB:** music genre labels need to be checked before being used, some songs are not present inside the iTunes database and/or have different song titles, thus some music genre labels might be missing or wrong. 

For our project, we manually checked if the labels were correct (limited to the data we used), thus we can't guarantee that all the genre labels are available and correct.

### Data download

[Data Download](Data_Download.ipynb) allows the user to download all the top 200 charts in the selected time span for the selected nations. Once the files containing the "plain" top 200 have been downloaded, [Download features](Download_features.ipynb) is used to extract and store features for each song.

### The project
 [THE_IMPACT_OF_COVID-19_IN_MUSIC_INDUSTRY.ipynb](THE_IMPACT_OF_COVID-19_IN_MUSIC_INDUSTRY.ipynb) contains the jupyter notebook of our project. We exported the notebook to HTML format in  [THE_IMPACT_OF_COVID-19_IN_MUSIC_INDUSTRY.html](THE_IMPACT_OF_COVID-19_IN_MUSIC_INDUSTRY.html), so you will just need a browser to open it. 
 If you're not a Python user/developer and you're interested just in our conclusion and data analysis, just go on with the HTML file.
 
 # Data sharing
 We don't own any rights on the data, it has been downloaded using public available APIs and dataset from Spotify and iTunes. If you would like to contribute to improve the data quality or increase its quantity, feel free to do it and contact me. 
