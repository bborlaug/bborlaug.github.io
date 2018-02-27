---
layout: post
title: "Make News Credible Again"
---  

The spread of deliberate misinformation ("fake news") online presents a serious threat to democracy by undermining the prerequisite of a well-informed electorate. For our capstone project in UC Berkeley's MIDS program, we explored a number of machine learning-based approaches for identifying "fake news" in two of its most common forms - clickbait and propaganda.  

The focus of our project was on building a data product from the ground up. We trained an ensemble (naive bayes + boosted decision trees) text classifier on a corpus of "credible" and "non-credible" articles scraped from the web. For three months in 2017, we exposed the fully trained model for public requests via an API and web application. We created dynamic visualizations to explore the model's performance and learned patterns over time.  
<br>
<img src="/img/mnca_clustering.png" alt='term-frequency clustering' style="width: 80%; margin: auto; display: block">

This project provided me with my first opportunity to see a product through to production.  While not ground-breaking by any measure, our work suggests that traditional natural language processing techniques can be used to derive predictive features from news article text.  

  
### Additional Resources
__Blog__: [Building a "Fake News" Classifier][medium]  
__Project__: [MIDS Spring 2017 Capstone Project Page][mids]  
__Application__: [https://classify.news][app]

[medium]: https://medium.com/@bborlaug/building-a-fake-news-classifier-pt-1-3-7a8c3631e19e
[mids]: https://www.ischool.berkeley.edu/projects/2017/make-news-credible-again  
[app]: https://makenewscredibleagain.github.io/
