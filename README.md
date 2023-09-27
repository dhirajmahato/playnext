# Playnext
Recommendation for the next track. 
Recommendation systems are available in all areas: news feeds, streaming video and audio services, and online stores.

#### Spotify
Spotify did not invent a new algorithm but rather combined 3 of the best ones that are used in this area.

3 models to create playlists with recommendations:
- **collaborative filtering** : collaborative (recommendations based on similarity of users’ preferences and using matrices with ratings for each content piece, in our case — a song)
- **NLP** for text analysis :
- **audio models** for audio file analysis: analyzes the song using a neural convolutional network and creates a spectrogram. After passing through the network, the algorithm knows the characteristics of the song — its volume, timbre, size, harmony, etc. eg: **Discover Weekly**

Note: **content-based** (recommendations based on the similarity of content or, in our case — attributes of two songs) - main idea of a content-based recommendation system is to extract keywords from the description of a song that a user likes, compare them with the keywords from the other songs, and, based on this, recommend similar songs to the user.

*These recommendation systems do not require any additional actions on the user's side.* <br/>
A person simply installs the application and registers, listens to his favorite songs, makes playlists... And the more data we have about his preferences, the more accurate our song recommendations to him become. 

Hybrid model of a recommender system, which unifies the advantages of several models while neutralizing their drawbacks and in such a way reaching high accuracy.
