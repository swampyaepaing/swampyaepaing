# Twitter Sentiment and Socioeconomic Status in New York City (2020)

**Collaborative university project | Natural language processing | Spatial analysis | Python**

## Team
Swam Pyae Paing, Mark Berezovskyi, Samuel Dribsa.

## Research question
How was COVID-19-related Twitter sentiment distributed across New York City in 2020, and what relationship did the available data suggest between income and sentiment?

## Approach
The team processed tweets, applied text cleaning and sentiment scoring, explored sentiment across ZIP codes, and examined association with neighbourhood income. The report describes Dask, Python, TextBlob, visualization, regression, and clustering.

## Reported findings
The report finds many neutral tweets and a small estimated negative coefficient between income and sentiment. The reported linear regression R² is **0.001356**, which indicates extremely low explanatory power, not meaningful predictive performance. These findings are **associations**, not evidence that income caused changes in sentiment.

## Sources and limitations
[Original project notebook (Google Colab, permissions may vary)](https://colab.research.google.com/drive/1dpvhGJbZ4-lti6kX3WQla_pM3SlyV4Dl?usp=sharing)

The analysis was conducted as a team project. The original notebook uses Google Drive paths, external input datasets and saved execution outputs; it has not yet been made fully reproducible on GitHub. Twitter samples and spatial aggregates can be subject to selection bias; sentiment labels also have measurement error.

## Portfolio status
This page documents the research report and is not a claim of a production NLP system.
