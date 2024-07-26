## Event Data from the 2018 World Cup

Finalized data is cleaned_events_world_cup2018.csv

This repo contains data from the 2018 World Cup in Russia. It was collected by Luca Pappalardo and Emanuele Massucco and is available on the [figshare platform](https://figshare.com/collections/Soccer_match_event_dataset/4415000/5). There is also a GitHub repo explaining how to work with the data (here)[https://github.com/Friends-of-Tracking-Data-FoTD/mapping-match-events-in-Python]. The data has led to multiple papers, including:

- Pappalardo et al., (2019) "A public data set of spatio-temporal match events in soccer competitions", _Nature Scientific Data_ 6:236, https://www.nature.com/articles/s41597-019-0247-7

- Pappalardo et al. (2019) "PlayeRank: Data-driven Performance Evaluation and Player Ranking in Soccer via a Machine Learning Approach." _ACM Transactions on Intellingent Systems and Technologies_ (TIST) 10, 5, Article 59 (September 2019), 27 pages. DOI: https://doi.org/10.1145/3343172

They collected their data from Wyscout and follow the data definitions from the (Wyscout data glossary)[https://dataglossary.wyscout.com/]. You can find information on the coordinate system used in the data [here](https://apidocs.wyscout.com/#section/Data-glossary-and-definitions/Pitch-coordinates).

![Image of Pitch Coordinates](https://apidocs.wyscout.com/assets/images/WyscoutDataCoordinates.png)

The authors have much more data than just the World Cup from 2018, but this repo exists to simplify the data (mapping player names to player IDs, team names to team IDs, etc.) and to provide a simple way to access the data for my students in my Python for Data Analytics course at Queens University of Charlotte.

In the repo, you will find the original event data, the original player data, the original team data, the mapped event data, and the Jupyter notebook that I used to map the data. The data is in JSON format. I have also included an .ipynb file with an example of how to calculate distance between two points on a soccer field.
