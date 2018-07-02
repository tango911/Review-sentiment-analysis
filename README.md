# Review-sentiment-analysis
I take a supervised approach to the problem and 50,000 movie reviews for building my training data. 
I investigate an efficient method to build a strong model for extracting the features that contain sentimental information and deploy it on a web page.
## Problem Statement and Data Description
My goal was to calculate the polarity of sentences that I had extracted from the text of reviews. I had modeled sentiment from movie reviews and tried to find out how this sentiment matches with the success of thes movies. 
 I have used the large dataset of movie reviews from the Internet Movie Database (IMDb) that has been collected by Maas et al. (A. L. Maas, R. E. Daly, P. T. Pham, D. Huang, A.Y. Ng, and C. Potts Learning Word Vectors for Sentiment Analysis. In the proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies, pages 142–150, Portland, Oregon, USA, June 2011 Association for Computational Linguistics). The movie review dataset consists of 50,000 polar movie reviews that are labeled as either positive or negative; here, positive means that a movie was rated with more than six stars on IMDb, and negative means that a movie was rated with fewer than five stars on IMDb. 
## Modules
1. App.py          #for local hosting  
2. out-of-core.py  #model training
3. Vectorizer.py   #preprocessing
4. templates       #HTML templates 
