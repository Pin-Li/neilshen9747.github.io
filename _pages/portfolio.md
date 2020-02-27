---
layout: archive
title: "Data Analytical Project"
permalink: /DataAnalyticalProject/
author_profile: true
---

[Humana-Mays Health Analytics Case 2019 Competition - A Predictive Analysis Using Python](/Humana_May_Case_Competition.html)
![](/images/humana-mays.png)
We predicted probability of long-term opioid use for 13,997 patients based on four-year medical records utilizing Python by conducting exploratory data analysis, data cleaning, feature engineering, and predictive modelling to enable Humana identify patients at risk for opioid overdoses and initiate intervention procedures, reaching prediction accuracy 87% and ranking in the 90th percentile of participants.

---
[Kiwi Bubble VS Mango - Casual Analysis on Consumer Choice Data using Multilogit Choice Model](/pdf/PricingAnalyticsPJ2.pdf)
![](/images/PricingAnalyticsPJ2.png)
My team conducted casual analysis on customer choice data by using multilogit choice model, and then we use k-mean clustering to segment customers and detect the Nash-Equilibrium of Kiwi company and Mango company. Check our analytics process using R.

---
[Estimating Car Demand - Casual Analysis on Sales Data](/pdf/PricingAnalyticsPJ1.pdf)
![](/images/PPJ1.jpeg)
My team conducted casual analysis, including linear regression with fixed effect, linear regression with instrumental variable, to exploit the demand of car models. Check our analytics process using R.

---
[Twitter Airline Customer Sentiment Analysis - Natural Language Processing Using Python NLTK Package](/pdf/Twitter%20-%20Natural%20Language%20Processing.pdf)
![](/images/twitter.png)
I predicted customer sentiment from Tweets by conducting natural language processing, including word-tokenization and TFIDF modeling, and leveraging machine learning algorithm, such as Naïve Bayes Classifier and Support Vector Machine, reaching 80% prediction precision. Check my python notebook.

---

[911 Emergency Call - A Data Visualization Project Using Python](/911_descrptive_analysis.html)
![](/images/911%20Projct.png)

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
