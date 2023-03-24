# msbx_5420_group3
Project Repo for Group 3

### About the Dataset: 
Source: https://www.kaggle.com/datasets/kamaruladha/mental-disorders-identification-reddit-nlp

### Dataset Information:

title: The title of the post (String).
selftext: The contents of the post (String).
created_utc: The time of when the post was published (Integer - UTC format).
over_18: Whether the post is >18 or otherwise. (>18 posts may be labelled for NSFW - Nominal Values).
subreddit: The subreddit where the post was posted on. (Can be used as the class label - String).

### Background:
The dataset contains 5 columns and around 700k rows of text data from different subreddits. The motivation behind this was to attempt in identifying different kinds of mental disorders via text in order to emphasize patients' security. Based on recent years, there have been a few cases of sensitive medical information being leaked in which it may jeopardize the patients' safety. Thus, by training a model with this dataset, it may help the patients to self-diagnose themselves. As of now, there are loads of depression tests online that only detects via a questionnaire. So, this would be one of the first AI-driven approach in solving mental health issues.

### Issues with the dataset:
Some of the data were removed for the selftext attribute (probably by the original author or might have received reports). On top of that, some posts do not have that much descriptive context for both title and selftext attributes. Furthermore, the dataset is field with "troll" posts that would only disturb the learning process of the model. The troll post may look something like this ("I AM IN YOUR WALLS/FLOORBOARD/CEILING/etc). The purpose of these troll posts are still unknown. Thus, heavy preprocessing is needed to ensure that the model is only fed with high quality data.

