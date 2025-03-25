# Data Analytics and Engineering Portfolio: Casey Cushing

Welcome to my portfolio!

The pipelines using a Serverless architecture will have multiple repositories (linked from this page).

# Audible.com Data Cleaning and Analysis

My preffered way to consume books is through audiobooks, so when I came across the dataset on the platform Kaggle, I wanted to see what insights I could uncover.

**Data Source:** Kaggle.com

[The Jupyter Notebook](https://github.com/ccdatapdx/Data-Analysis/blob/master/audible-data-cleaning-analysis.ipynb)

# UN Speeches Processing and Analysis

Sometime ago, I had found this collection of text files of UN Speeches from 1970-2020. I thought it would be interesting to process it with the Spacy NLP Library and see what UN Ambassadors were speaking about over the years.

**Data Source:** I don't recall the website I downloaded it from, but the data is linked from my repository below.

[Speech Text Files](https://github.com/ccdatapdx/Data-Analysis/tree/master/TXT)

[The Jupyter Notebook for analysis](https://github.com/ccdatapdx/Data-Analysis/blob/master/un-speeches-analysis.ipynb)

[The script used to process the files](https://github.com/ccdatapdx/Data-Analysis/blob/master/un_speech_processing.py)

# Techmeme Headlines Pipeline
![system diagram of youtube comments pipeline](https://github.com/ccdatapdx/Portfolio/blob/master/techmeme_headlines_pipeline.png)

### [Live Dashboard!](https://lookerstudio.google.com/reporting/ebc8b4a7-48cd-4ac2-8fc2-b1b528b53459)


## Tech Stack:

**Data Source:** https://techmeme.com/

**Repositories:**

[techmeme-headlines](https://github.com/ccdatapdx/techmeme-headlines)

[techmeme-llm-processing](https://github.com/ccdatapdx/techmeme-headlines)

**CI/CD:** GitHub Actions

**Compute:** AWS Lambda

**Data Transformation:** DBT Cloud

**Data Warehousing:** Google BigQuery

**Dashboarding:** Looker Studio




## Inspiration:

When I was doing media data analysis, the PR account executive folks, doing communication with press to drive news coverage, would use a site called Techmeme.

Once I learned about this practice after helping out on some reporting on the site for mentions of various tech brands, 
I started using it myself to follow tech news.

It is a news aggregator, but what differentiates it is human curation of news stories, written by tech journalists who are very influential.

The PR folks, obviously viewed it as meaningful to get news placements from the various outlets and particular journalists.

From their site:
> "Our experience leads us to believe that a thoughtful combination of both algorithmic and human editing offers 
the best means for curating in a space as broad as technology"

For me, with the incredible amount of news that is out there, I find it very convenient to be able to go to one source for overall
news and find out if something big has happened.

I would like to be able to not only see the quantity of companies, but to be able to search the headlines 
(which only go back so far on the site itself). 




# YouTube Comments Pipeline
![system diagram of youtube comments pipeline](https://github.com/ccdatapdx/Portfolio/blob/master/youtube_comment_pipeline.png)

### [Live Dashboard!](https://lookerstudio.google.com/reporting/6904e416-421f-45dc-b7c6-ff9e851044c3)

## Tech Stack:

**Data Source:** YouTube Data API

**Repositories:**

[yt-data-api](https://github.com/ccdatapdx/yt-data-api)

[yt-comments-nlp-process](https://github.com/ccdatapdx/yt-comments-nlp-process)

**CI/CD:** GitHub Actions

**Compute:** AWS Lambda

**Data Transformation:** DBT Cloud

**Data Warehousing:** Google BigQuery

**Dashboarding:** Looker Studio

## Inspiration:

As both an avid consumer of YouTube content, and technology- I was interested in extracting data from YouTube comments. Apart from just plainly being interested in seeing the data, this project has multiple use cases:

### Influencer Marketing (Paid Media):

This type of marketing has increased substantially over the years over more traditional marketing.

This makes sense given the increased trust that influencer audiences have for their given creator. They are much more likely to take their opinion seriously, especially when the marketing doesn't seem overtly biased.

The beauty of this type of marketing is--through the strategic choice of influencers, you can secure a positive review of your product and at the same time, not have it appear to be overtly biased. This is due to the strategic choice being based on the influencer's existing opinion, so you already have a good idea of what they are going to think.

### Executive/Manager Reporting:

With internet content, there can often be a lot to review (as you would expect companies to do with investments). Considering the breadth of responsibilities of executives/managers, you would expect this responsibility to be delegated to others (watching/looking at the content) and then providing an analysis for reporting.

This tool would help this effort by:

1) Shortening time it takes to get to high-level insight

2) Having main themes of a video (or several videos in a campaign) ready to go in easy-to-read charts

3) Supplementing manual human analysis with data-based charts

### Large creators/influencers:

With any social media creator/influencer there is a varied amount of engagement they have with their community. For those creators who have or want to have a "pulse" on what the community is saying- this tool could be immensely helpful.

With size of audience and reach, comes a few things:

1) Far too many comments to possibly keep up with 

2) More likely to have a "manager" who may or may not want to keep an eye on the community
