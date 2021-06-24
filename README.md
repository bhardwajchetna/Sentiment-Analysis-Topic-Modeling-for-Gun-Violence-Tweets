# Sentiment-Analysis-Topic-Modeling-for-Gun-Violence-Tweets
A goal of this project was to identify the key topics revolving around gun violence issues and help nonprofits and relevant government institutions to better understand the public opinions about the initiatives that they proposed to address gun violence issues and take in-time corrective measures to guide the campaigns to a successful trajectory. 

Data consists in the form of real-time tweets collected under three broad categories:
1. General tweets related to guns and the second amendment.
2. Gun Control Tweets related to gun opposition activists .
3. Gun Rights tweets related to firearm rights.

| Type | Keyword |
| --- | --- |
| General | "gun", "guns", "second amendment", "2nd amendment", "firearm", "firearms"|
| Control | "gun sense", "gun sense patriot","vote gun sense","gun control now", "moms demand action","moms demand"," demand a plan","no way nra","gun skill people", "gun violence","end gun violence","gun violence prevention","assault weapons",  "license","gun safety"|
| Rights | "no gun control", "pro gun", "no gun registry", "vote gun rights", "fire arm rights", "gun grab", "gun friendly", "gun rights", "right to carry", "concealed carry" |


Twitter API to Kafka: Using Kafka's "Producer" module to collect data from Twitter streams and preserve it in the form of queues. 
Kafka to Bonsai: Kafka module "Consumer" used to read the logs for the three topics and process the data.
Modelling: 
Sentiment Analysis: Vader & Spark NLP 
Topic Modeling: Spark NLP & Zero-shot classifier

*Tableau:*
Th Results in form of Sentiments (Positive/negative/Mixed) and Topic Classification were viewed on Tableau for a thorough analysis. 
