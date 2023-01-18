# Netflix-Movies-and-TV-Shows-Clustering
Netflix-Movies-and-TV-Shows-Clustering

## *Project Name: Netflix Movies and TV Shows Clustering*
![image](https://user-images.githubusercontent.com/113257700/212488591-29487991-7208-41be-a752-41f9459de2e9.png)

In this project dataset consists of tv shows and movies available on Netflix as of 2019.The aim of this project is to find clusters.In this project, required to do: (1)Exploratory Data Analysis, (2) Understanding what type content is available in different countries, (3) Is Netflix has increasingly focusing on TV rather than movies in recent years, (4) Clustering similar content by matching text-based features.

Data Description:

show_id : Unique ID for every Movie / Tv Show

type : Identifier - A Movie or TV Show

title : Title of the Movie / Tv Show

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Releaseyear of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Genere

description: The Summary description
## **Conclusion**
I have successfully implemented Unsupervised Machine learning algorithm where I have clustered the data on Netflix dataset and divided the dataset into seven clusters.

From elbow,sillhoute score and Dendrogram , discovered that Optimal number of clusters are 7.
Netflix has 5377 movies and 2410 TV shows, there are more number movies on Netflix than TV shows.
Highest number of movies released in 2020 The number of movies on Netflix is growing significantly faster than the number of TV shows. I saw a huge increase in the number of movies and television episodes after 2015. there is a significant drop in the number of movies and television episodes produced after 2020. It appears that Netflix has focused more attention on increasing Movie content than TV Shows. Movies have increased much more dramatically than TV shows.
International Movies are the top most genre in netflix, followed by Dramas, comedies and international movies.
Most of the movies have duration of between 70 to 150.
Unitated states has the highest number of content on the netflix ,followed by india.
TV-MA has the highest number of ratings for tv shows. It means that Majority of Content is for Adults.
Through TFIDF Vectorization, I created a total of 20000 attributes.
I used Principal Component Analysis (PCA) to handle the curse of dimensionality. 3500 components were able to capture more than 80% of variance, and hence, the number of components were restricted to 3500.
Using the given data a simple recommender system was created using cosine_similarity and recommendations for Movies and Tv Shows were obtained.

