# What are we talking about when we are talking about COVID vaccine?
## Proposal:https://github.com/wdnmd97/DH140_Group_Project/blob/main/Group%20Assignments/Group%20Assignment%20%231:%20Project%20Proposal.md
## Team Roles:
* Kai Watanabe
  * Kai’s primary role in this project will be to determine how to take the analyzed twitter data and combine it with geocoded census data. Through this endeavour, we can learn more about the communities tweeting about COVID vaccine information. Analysis will include where the most tweets are coming from, and what the racial, economic, and political distribution of these communities are. By visualizing this data, it can be easier to understand how different countries are delivering COVID vaccine updates to their communities, and what effect these methods of distributions have on dividing or unifying the opinions of their citizens.
* Jack (Yueshuwei Wu)
  * In charge of analyzing the contents that users post on Twitter regarding to the COVID vaccine. Jack will analyse patterns of content quantitatively using statistical methods and qualitative methods to analyse meanings of content within texts. 
* To clarify, although we have designated roles, we will not be working exclusively from each other. We divided the work up in areas where we were most comfortable/interested, but we have and will continue to collaborate with each other if the other team member requires assistance or consultation
## Status update
* As of now, we’ve been able to scrape over 4000 tweets pertaining to the COVID19 vaccine. Our dataset is global, and our largest datasets are from the UK, US, and the United Arab Emirates. At our current stage, we have been able to divide tweets by region and divide each user’s tweets into keywords using GeoText, and by tokenizing the tweets. This process allows us to calculate sentiment scores for each tweet, which indicates whether they show general approval or disapproval for the vaccine. As can be seen by the data, most community members are neutral but some communities fluctuate in the balance of positive and negative sentiment scores. We think that mapping this data, and doing census analysis on some of the biggest cities could help us make conclusions about why the sentiment scores are distributed in the way that they are.
* What is working:
  * We have sucessfully extracted locational data from the users' location description for mapping purposes.
  * We've find a way to evaluate the sentiment of a tweet as a feature of public vaccine approval.
* What is not working:
  * Did not find strong correlation between our discovery and the census data like race profiles.
## Data update
* Data source: Pfizer Vaccine Tweets https://www.kaggle.com/gpreda/pfizer-vaccine-tweets
* We want to do a detailed analysis on the public's approval of the Pizfer COVID vaccine. By now, we have found that the majority of Twitter users either have a positive or nuetral sentiment score on the vaccine, which may indicates acceptance and approval. Interestingly, we observed a siginificantly more negative sentiment scores from Indian users.
## Concerns
* Major Concerns
  * Since our dataset is global, it is near impossible for us to gain data on specific regions of any city. The census analysis can help us to better understand why sentiment scores may be distributed, but they will not be able to provide definitive answers. Mapping this data could not be as informative as one would expect, so it may ultimately be better to express our data using graphs. However, since this is a geomapping course, I wish to find ways on using mapping somehow.  
* Minor concerns
  * How can we extract topics from tweets? (Working on some math right now.)
