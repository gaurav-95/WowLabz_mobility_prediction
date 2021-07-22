# WowLabz_mobility_prediction

 Mobility Prediction task using latitute and longitute values with visualization.

Problem Statement:

1. To predict the path of a new entity given a record of trajectories of people/records in terms of latitude and longitude values with timestamps.

2. To visualize the highest likely path and plot it on a map that shows the trajectory of the new entity for 40 instances/time-periods of the path. (Lower timestamp intervals of 1, 10 or 15 mins preferred)

Idea reference origin url: https://www.nytimes.com/interactive/2019/12/19/opinion/location-tracking-cell-phone.html

Dataset used (or under consideration):

People:
https://www.microsoft.com/en-us/download/details.aspx?id=52367
https://archive.ics.uci.edu/ml/datasets/GPS+Trajectories


Car:
https://smoosavi.org/datasets/dact
https://www.microsoft.com/en-us/research/publication/t-drive-trajectory-data-sample/?from=http%3A%2F%2Fresearch.microsoft.com%2Fapps%2Fpubs%2F%3Fid%3D152883

Approach:

1. To use RNN to predict the path of the object.
2. To cluster the paths defining hexagonal areas. Then find the probabilities of the path crossing that area.

Conclusions:

LSTM does better compared to bi-directional and gru in path regression

Deadline:

Friday, 23rd July, 2021 EOD/ Saturday 24th July, 2021 Afternoon

Links to Resources:

https://github.com/uber-web/kepler.gl-data
https://www.quadrant.io/resources/location-data
https://datarade.ai/
https://github.com/anitagraser/movingpandas
https://www.kaggle.com/stoney71/new-york-city-transport-statistics?select=mta_1712.csv
https://medium.com/nightingale/twelve-million-phones-one-dataset-zero-privacy-an-interview-with-the-new-york-times-stuart-a-e2988d398ba3
https://archive.ics.uci.edu/ml/datasets/GPS+Trajectories
https://crawdad.org/
https://smoosavi.org/datasets/
https://smoosavi.org/datasets/dact
https://data.cincinnati-oh.gov/Efficient-Service-Delivery/Vehicle-GPS-Data-Department-of-Public-Services/b56d-ydmm
https://archive.ics.uci.edu/ml/datasets/Taxi+Service+Trajectory+-+Prediction+Challenge,+ECML+PKDD+2015
https://snap.stanford.edu/data/loc-brightkite.html
https://snap.stanford.edu/data/loc-gowalla.html
https://privamov.github.io/accio/docs/datasets.html


