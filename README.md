# Geographic Sentiment Analysis of Reddit Data
This dashboard is created in support of the Applied Data Science coursework. It displays the sentiment distribution of comments within the `r/Europe' community on the social media platform *Reddit*, with specific emphasis on how sentiment varies based on the author's national identity. A dataset containing over 65,000 comments is produced, which is then analyzed under different sentiment models. Metrics are gathered for the undirected (posted from a country) and directed (posted toward a country) sentiment for these comments. Topic Modelling and Named Entity Recognition are carried out to allow visualisation of sentiment based on specific topics or towards entities.


## Table of Contents
- [Dashboard](#dashboard)
- [Usage](#usage)

# Dashboard
![](demo/choropleth.png)
## Choropleth with hover information about sentiment:
![](demo/hoverinfo.gif)

## Change sentiment model:
![](demo/model.gif)

## Change topics:
![](demo/topic.gif)

## Change sentiment type:
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



# Usage

Provide instructions on how to install the project and its dependencies. Include any necessary commands or steps.

```bash
pip install my_project
