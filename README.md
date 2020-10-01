# BigData-Module-16
 Thechallenge demonstrate using big data dataset, setting up an AWS RDS postgres database, use Google Colab Notebook to perform ETL on a big dataset, then analyze the data outcome and provide an anlysis.
 
 Link to my ETL and analysis on Google Colab:https://colab.research.google.com/drive/1RxXymIAccaeeRAKsLqbA7pDfaX_A7gb4?usp=sharing
 
## Analysis:
To summarize our findings about vine paid vs non paid data:
1. Total count of reviews: 10,779 paid, 2,623,758 non-paid.
2. Total 5 star reviews: 5,557 paid, 1,650,924 non-paid.
3. Average star: 4.30 paid, 4.18 non-paid.
4. Number of helpful votes: 28,568 paid, 4,403,524 non-paid.

It appears that a similar trend between the paid versus non-paid at a high level. We can further see that about 80% and 83% of total votes are helpful votes (helpful/total) for paid vs non-paid respectively. If we filter out "the noise" by only looking at reviews that have 3 or more votes and are considered helpful. Then, we can see the average star rating across reivews as 4.21 and 4.18.

To conclude that vine reviews are similar to non-paid review therefore trustworthy. 
