# Anime-Recommendation System

# *The Dataset*

https://www.kaggle.com/CooperUnion/anime-recommendations-database
This repository was posted on Kaggle by CooperUnion in 2017 with a goal to Build a better anime recommendation system based only on user viewing history. This data set contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this data set is a compilation of those ratings. It has two CSV files, anime.csv and rating.csv.

# *Features*

*Anime.csv*

anime_id : myanimelist.net's unique id identifying an anime.

name : full name of anime.

genre : comma separated list of genres for this anime.

type : movie, TV, OVA, etc.

episodes : how many episodes in this show. (1 if movie).

rating : average rating out of 10 for this anime.

members : number of community members that are in this anime's "group".


*Rating.csv*

user_id : non identifiable randomly generated user id.

anime_id : the anime that this user has rated.

rating : rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating).


