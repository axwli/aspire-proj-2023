# ASPIRE Project 2023.

Research project advised by Dr. Seth Frey. Presented at the 2023 ASPIRE Symposium.

## Abstract
In 2017, Taylor Swift released an album titled "Reputation" to rebuild her image after a decade-long feud with Kanye West. This project aims to explore the shift in public opinion on Twitter following the album's release. We used sentiment analysis tools to quantify negative and positive sentiment towards Taylor Swift before, during, and after "Reputation" was released. Using topic modeling, we identified clusters of similar words in the tweets. Our results show that, on average, opinions towards Taylor Swift did not change, though there is indication of a shift in opinion towards Kanye West.

## Methodology
- Tweets mentioning Taylor Swift were collected as JSON files and then converted into Pandas DataFrames.
- Each data set was cleaned to filter out non-English tweets. URLs, line breaks, and tags were removed from the contents of each tweet.
- Sentiment labels (negative, neutral, positive) and sentiment rates were attached to each tweet in all three data sets. Each rate was averaged out according to the label and dataset it belonged to.
- BERTopic topic modeling was applied on all three data sets with 15 clusters each.

## Findings
- Positive sentiment slightly decreased and negative sentiment remained relatively the same.
- There was no change in sentiment during and after the release of the album.
- In the "After" phase, one of the clusters mentioned "kanye" with negative wording such as "death" and "threat."

### Acknowledgements
Special thanks to Seth Frey and Shyam Agarwal for providing feedback and advice.
