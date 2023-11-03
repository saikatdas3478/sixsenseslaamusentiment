s## Six Senses Laamu sentiment analysis

Six Senses Laamu is a luxury Maldives resort featuring a combination of on-land and over-water villas constructed of sustainable materials. Many customer have visited such place and provided a brief and expressive review there. 
In this documenty, 

This repo is about detecting the emotion of people on visiting this amazing place and flag sentiment using scrapped data from tripadvisor. For scrapping data, I have used Beautiful Soup library and scrapped around 2913 reviewss in total.
The document includes steps for data preprocessing, tokenizing, pos-tagging, lemmatizing, and finally detecting sentiment of each review of the place. 
For sentiment analysis, I have used the VaderSentiment library and its sentiment intensity module. 
Most of the reviews has been flagged to be positive, so it actually aligns with the company website where they also suggested a overwhleming postive reivew there.
Finally, a pie chart presented 99.3% of positive review and only 0.5% negative review from this analysis. 
Also a wordcloud has been generated, where it clearly shows "amazing", "honeymoon",  "best", "recently" and "perfect" are the most often used words by the customers in their review.

