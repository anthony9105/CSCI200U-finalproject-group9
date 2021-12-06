# CSCI2000U-finalproject-group9
Introduction:

The dataset focused on movies was chosen for many crucial reasons. First being that it is something everyone in this group has a passion and real interest in. This makes it easier for us to come up with questions we are genuinely fascinated about. Another reason is due to the fact that the dataset, based on our analysis questions, will output staightforward information that can be clearly visulized and intrepeted to come to definite conclusions. Most of our questions are in some way about the rating of specific movies or directors. This is becuase keen on understanding what makes a great, top rated movie. Is it due to the runtime, genre, director, or even the year it was released in. The group members in this group are, Paul Hruda, Garrett Kawabata, and Anthony Liscio> All three group members contributed equally to all parts of the final project to make it an actual group effort. 

About Us: 

All of us in this group are immense movie lovers. Not all types of movies our are favorites, but nine out of ten of them are. When it comes to marvel movies most of us are there opening night no matter what, so its safe to say action and adventure is our perfered genre of choice. That does not stop us from enjoying all types of movies from mystery to comedy. This is crutial in understanding why we chose this specific data set and how effortless it is for us to come up with meaningful questions and anaylsis material that we actually care about.   

Description of data: 

The dataset chosen for our group project is focused on movies. More specifically top rated movies. The data was collected from past movies of all types of genres rated on imdb, into a list from highest rated to lowest. The chosen dataset also includes the years the movies were released in, runtime, director, and more. Also the datset was accesed through a kaggel source and is credited in our proposal. 

Analysis of the data: 

For our data set there are 1000 data records (movies) ranging from 1920 to 2020 with 548 different directors. Some data had to be cleaned up depending on the question since some older movies did not include a met score. In total there are 14 different game genres:

['Drama', 'Crime', 'Action', 'Biography', 'Western', 'Comedy', 'Adventure',
'Animation', 'Horror', 'Mystery', 'Film-Noir', 'Fantasy', 'Family', 'Thriller']

Each Column of the dataset discribed:

• Poster_Link : link to the poster image that is used on IMDB website

• Series_Title : Title of the Movie

• Released_Year : year the movie was released

• Certificate : age rating of the movie

• Runtime : length of the movie in minutes

• Genre : genre of the movie

• IMDB_Rating : movie rating by IMDB

• Overview : brief description of the movie

• Meta_score : critic score of the movie (0-10)

• Director : director of the movie

• Star1, Star2, Star3, Star4 : first four stars of the film

• No_of_Votes : votes

• Gross : money made by the movie

Exploratory Data Analysis: 

1. Based on the results from question one we now know that the top three genres rated by IMDB are Western with an average of 8.00 out of 10, Film-Noir with a 7.99 average, and Mystery with an average of 7.97. With all three rating being so close it seems that with acouple more high rated movies from the second or third placed gengres, Western could no longer be the top rated. 

2. Based of the results from collecting the average IMDB ratings per runtimes appears to be inconclusive. This is largely due to the fact that correlation coefficient between the two is 0.24. With a correlation that low it is not wise to come to a firm conclusion on our finding. Hopefully in the future we can analyze more similar data and come up with a solution that outputs a better coefficient to evaluate.  

3. Not suprisingly the top rated direcctor that is withing the top reacurring directors is Christopher Nolan, 0.2 higher rated then Stanley Kubrick at second highest rated. However the most the most reacurring director within the data set is Alfred Hitchcock	with a grand total of 14 movies. Since he only directed about fifty films that means that twenty eight percent of his movies made it into the top one thousand of all time.  

4. There were three genres that scored an average over 80, these genres being western, animation, and film-noir higher than most of the others. The film-noir genre received the highest average meta score of 91, with animation and western films both roughly around an 81 average. For the other 11 genres, their meta scores averaged between 73 and 77 out of a max of 100. Action had the lowest score amongst the 14 genres, with a score of 73.79.

5. Surprisingly 1941 and 1942 had the highest average Meta Score of 100, meaning they only had perfect movies those years. This conclusion can however be misleading, since only one movie for each year made it into our data set. None the less those years based off our analysis had the highest average Meta Score of 100 out of all years in the data set. Another notable statistic is that every year in the top ten are below the 1960's and with only an average of two or three movies realeased in our data set. This leads us to believe that alot of the more recent years did not make the highest average Meta Score list due to the fact that they had way more movies, making it more likely for some of them to bring down their average meta score.

6. For the majority of the certification types, the average runtime of the films are over 100 minutes long. Only one certificate had an average lower than 100, which was films rated TV-PG. These films ran on average just a little longer than an hour and a half, at around 93 minutes. Films that were unrated or did not receive any certificate had the longest average runtime of 3 hours. Following the unrated category are TV-14, 16, and UA certificates, with average runtimes almost 50 minutes shorter.

7.  Therefore the min runtime is 45 minutes while the max runtime is 321 min in the top 1000 rated movies. The min runtime IMDB rating is 8.2 and the max runtime is also 8.2 meaning that we cannot draw a conculsion based on this analysis since both scores are the same. Dissapointingly the resulting meta scores were also a let down. This is because the min runtime movie did not have a meta score to display. The max runtime meta score is 89 which is above average, but again no conclusion can be drawn for which movie runtime was higher rated since the two scores can not be compared.

8. Based off the results of question 8 we can analyze that the top rated director of all time according to IMDB is Frank Darabont with an average rating of 8.95. We found it interesting that five out of the ten top directors only had one movie within the top one thousand. This could mean that some of those directors could have made really poor movies with just one great success. This could then therefore lead us to the conclusion that the true greatest director, not according to IMDB but from our total analytics, is Christopher Nolan or Quentin Tarantino since they have eight movies within the top one thousand. This is simply because this means they are in the top ten most recurring directors and are within the top ten highest rated directors as well.   


Potential Data Science:

A potential idea when regarding potential data science based on our dataset is to determine what an ideal movie might look like to get the highest rating. This would be achieved by selecting the highest rated or most occuring director along the perfect analyzed runtime within the highest rated genre. This constructed outcome would scientifically have the poper elemnets to possibly become the perfect movie according to IMDB.    

Conclusion:

One major limitation based on this data set when concidering potential data science listed above is that the data set does not state what actor star in each given movie. This can be problematic if trying to see what makes a good movie, since a great actor can sometimes break or make a movie. This leads us to take interest in more data sets around movies that concern and reveal more about the actors in great movies for a possible future direction in analyzing data. One of the most suprising data formed from this data set is that the year 1941 and 1942 had the highest average Meta Score. Another not predicted our come based on our analysis is that the highest rated genre acorring to IMDB is the western genre. This is suprising in our oppinoin becuase with all the good actor movies released recently we assumed that action or adventure would have been the highest rated, but they did not even make top three.  
