# TVRatings_Project1

Clean and format datasets with Pandas
Use Matplotlib to create a total of 6-8 visualizations of your data (ideally, at least 2 per question you asked)


Project Members: Katie Corrion, Chelsea Johnson, Kellie Mullan, Tirhas


In this project we are going to find the most significant ratings on TV. These such variables are the network, show, gender and schedule.

----------------------------------------
## Research Q&A:

The data used is from the TVmaze API. TVmaze is a community of TV lovers and dedicated contributors that discuss and help maintain tv information on the web. The API maintains information pertaining to all shows currently on air internationally. 

This data was used to research ratings that pertain to networks and shows. We also were interested in gender demographics. And lastly, we wanted to know what days of the week had the top ratings. 

This type of data analysis would be useful for many reasons. Most networks are owned by large business conglomerates, which could dive into their networks’ ratings globally. This research could also be used by advertisers to have better informed pricing pertaining to days of the week, tv shows, and networks. TV Studios can apply the gender analysis to insure they are have equal representation of genders on air. 

The following are the questions we wished to answer by leveraging the wonderful python libraries for data analysis and data visualization:

## Question #1 - Which TV Networks are top rated?

In order to scrub the data to find the networks we first had to import the TVmaze API, focusing on the “show” endpoint. The “show” endpoint contains a multitude of information about all the tv shows currently on air. For example, Name, Genre, Status, Runtime, Premier Date, Schedule, Rating, and Network. In order to get a sampling, we pulled the first 50 pages in the API and organized the data by “Networks”and “Ratings.”We then ran summary statistics on the Data Frame we created to find the mean ratings for each network. 

Through data analysis we found the top rated Networks were:
- Star TV
- Smithsonian
- Channel 9 MCOT HD
- France 2
- ESPN 2
- Lifetime Movies
- CBS Sports Network
- BBC Scotland
- SUN-TV
- ZDF




We also found the lowest rated Networks were:
- ITV Be
- CNN
- TVP2
- Fox News Channel
- nick@nite
- MSNBC
- UP TV
- Gold
- CTC
- RTL
--------------------------------






## Question 2 -- What are the top rated TV Shows?

In order to answer this question, we had a very similar approach as our first question. We first had to import the TVmaze API using the endpoint for shows. We then created a new Dataframe with the focus on “Shows” and “Ratings.” We then sorted the data to find the top and lowest rated shows.

The top rated shows are:
- Louis Theroux’s Weird Weekends
- Kara Sevda
- Air Warriors
- Planet Earth
- Saint Seiya
- The Blue Planet
- The Band of Brothers
- Dragnet
- House Husbands
- Firefly


2. The lowest rated shows are:
- CNN Heroes
- What Would You Do?
- The View
- The Real Housewives of Cheshire
- LazyTown
- CNN Tonight with Don Lemon
- Teen Mom 2
- Dr. Phil
- The Factor
- Teen Mom OG
--------------------------------------------


## Question #3 -- What are the gender demographics for TV shows that are currently on air?

In order to investigate this question, we continued to use TVmaze API with the “shows” endpoint. We had to manipulate the data to filter through the cast by “Person” and “Gender.”  We found that 59.2% of actors currently on TV are male and 40.8% are female.


---------------------------------
## Question #4 -- How are ratings distributed over certain days of the week?

The TVmaze API end point for shows was used to dig into this question. We had to filter for “Days” and “Ratings.” We ran summary statistics on the data frame we created and found that Sunday had the highest average rating. 


------------------------------------



The following are the dictionaries were used:
Python
Jupyter Notebook
Pandas (for data analysis)
Matplotlib (for visualization)

