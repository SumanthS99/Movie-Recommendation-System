# Movie Recommendation System
Note: This project uses jupyter widgets which isn't supported in github. Please refer to the output screenshot separately attached.
This is a movie recommendation system that combines two methods: content-based filtering and collaborative filtering. It suggests movies based on similarity to the user’s input and the preferences of similar users.

## How It Works
## Content-Based Filtering
The system uses cosine similarity to find movies with titles similar to the user's input. This step helps match the searched term with the most relevant movie title.
## Collaborative Filtering
* The system identifies users who rated the specified movie (user's input) above 4 and checks what other movies they liked.
* It suggests movies that are popular among similar users.

Final recommendation will be a set of 10 movies "which are liked by similar users and are not just generally popular" - this way, we personalize the recommendations being made.
