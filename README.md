# MIR
This project is a part of the course Music Information Retrieval. 

#### -- Project Status: [Completed]

## Project Intro and Description
Our plan was to find out the main chords played in a big (small in the larger scale :)) amount of songs from the same genre. After finding the chords, we tried to mix them up in order to create a fully machine generated song. For this the 30 s songs didn´t give a good overview, because the music files were made from different parts of the songs. Plus some clips had only one chord. So it was hard to make chord progression. We implemented a machine learning algorithm for all of the music files and tried to find out if the songs were categorized correctly by the algorithm. We also added chord progession, which is common for blues and country. 

## Dataset
Data: gtzan dataset
The dataset consists of 1000 audio tracks each 30 seconds long. 
It contains 10 genres, each represented by 100 tracks. The tracks are all 22050Hz Mono 16-bit audio files in .wav format.

The genres are: blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock

### Methods Used
* Data Visualization and analysis
* Machine Learning
* Predictive Modeling

### Technologies
* Pandas, jupyter
* HTML

## Getting Started

1. Clone this repo.
2. Open this repo with Jupyter notebook.
3. The code is written in three repos.
4. To run these files, in each you have to run all cells from beginning.

### Notebooks contents:

#### MIR project_extraction.ipynb:
* dataframe creation per genre
* dataframe: genre, chords, first chord, most_popular_chords

#### MIR project analysis.ipynb:
* all chords spearately in dataframe per genre
* bar plots for each genre

#### MIR Project Prediction.ipynb:
* creation of dum dataframe
* creation of predicting model
* KNN
* RandomForestClassifier
* Added one progression => prediction again

#### Team Members:

|Name     |  Slack Handle   | 
|---------|-----------------|
|Georg Nero (https://github.com/georgica22us)| @georgica22us      |
|Maria Mängel (https://github.com/mariamangel)| @mariamangel        |

## Contact
* Feel free to contact with any questions.
