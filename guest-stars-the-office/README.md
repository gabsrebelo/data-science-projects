# Guest Stars in The Office
In this project, we will take a look at a dataset of The Office episodes, and try to understand how the popularity and quality of the series varied over time. To do so, we will use the following dataset: datasets/office_episodes.csv, which was downloaded from Kaggle [here](https://www.kaggle.com/datasets/nehaprabhavalkar/the-office-dataset).

This dataset contains information on a variety of characteristics of each episode. In detail, these are:

**datasets/office_episodes.csv**

* episode_number: Canonical episode number.
* season: Season in which the episode appeared.
* episode_title: Title of the episode.
* description: Description of the episode.
* ratings: Average IMDB rating.
* votes: Number of votes.
* viewership_mil: Number of US viewers in millions.
* duration: Duration in number of minutes.
* release_date: Airdate.
* guest_stars: Guest stars in the episode (if any).
* director: Director of the episode.
* writers: Writers of the episode.
* has_guests: True/False column for whether the episode contained guest stars.
* scaled_ratings: The ratings scaled from 0 (worst-reviewed) to 1 (best-reviewed).