# Geographic Sentiment Analysis of Reddit Data
This dashboard is created in support of the Applied Data Science coursework. It displays the sentiment distribution of comments within the `r/Europe' community on the social media platform *Reddit*, with specific emphasis on how sentiment varies based on the author's national identity. A dataset containing over 65,000 comments is produced, which is then analyzed under different sentiment models. Metrics are gathered for the undirected (posted from a country) and directed (posted toward a country) sentiment for these comments. Topic Modelling and Named Entity Recognition are carried out to allow visualisation of sentiment based on specific topics or towards entities.


## Table of Contents
- [Dashboard](#dashboard)
- [Supplementary Plots](#supplementary_plots)
- [How to Use](#usage)

# Dashboard - [link to full video demo](https://uob-my.sharepoint.com/:v:/g/personal/fy20856_bristol_ac_uk/EZu-SdbiKeFLtZJxxV8NWZgBClyL2PSqqOmKul_PeWyDbQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=vQGpWw)
> Choropleth of directed (mention) sentiment with VADER model
![](demo/map.png)
## Choropleth with hover information about sentiment:
![](demo/hoverinfo.gif)

## Change sentiment model:
![](demo/model.gif)

## Change topics:
![](demo/topic.gif)

## Change sentiment type:
> Changes both choropleth and timeseries plots
![](demo/direction.gif)

## Sentiment and emotion timeseries:
![](demo/timeseries_sentiment.png)
![](demo/timeseries_emotion.png)

## Sentiment and emotion timseries for chosen country:
![](demo/timeseries_usa.gif)

## Correlation of sentiment models animation:
![](demo/scatter.gif)

## Random subset of comments:
![](demo/comments.gif)


# Supplementary Plots
These additional plots supplement the information in the report.

> The correlation between the sentiment analysis models.
![](demo/model_corr.png)
>
> 
> The correlation between the two BERT emotional sentiment models. Anger is the highest correlated emotion.
![](demo/bert_corr.png)


# Usage

Clone into repository.

Run dashboard.ipynb.

To see dashboard: [use this link](http://localhost:8052/)

> [!WARNING]
> The dashboard is quite slow, please be patient. For a sped-up, full demo of its capabilities see [this video](https://uob-my.sharepoint.com/:v:/g/personal/fy20856_bristol_ac_uk/EZu-SdbiKeFLtZJxxV8NWZgBClyL2PSqqOmKul_PeWyDbQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=vQGpWw).
