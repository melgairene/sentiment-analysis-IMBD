# sentiment-analysis-IMBD
Explore how different machine learning and deep learning algorithms perform in the task of binary classification using movie reviews. 

In this project, I consider the problem of supervised binary classification in movie reviews from the IMBD data set (https://ai.stanford.edu/~amaas/data/sentiment/) [1] . This data set consists of 50000 movies, 25000 of which are negative and labeled with y = 0 and 25000 of them are positive an labeled with y = 1. The dataset given is originally divided into training and test data, but I mixed all the reviews together so that I always have 32000 reviews in my training set. I used the base codes in https://github.com/changhuixu/sentimentanalysis-using-python/ for the analysis with Naive Bayes and Support Vector Machines and the code in https://stackabuse.com/python-for-nlp-movie-sentiment-analysis-using-deep-learning-in-keras/, for the CNN and the LSTM network. 

My motivation for this project was twofold: to obtain familiarity with the code used in a breadth of real world applications and to actually identify which
kind of analytical technique was more useful for this particular task. My work led me to similar conclusions than those present in the literature: machine
learning technniques may be enough in some cases, with SVM being the best classifiers [2] and CNN work comparatively better than RNN when dealing with
short text [3].

[1] A. L. Maas, R. E. Daly, P. T. Pham, D. Huang, A. Y. Ng, and C. Potts, “Learning word vectors for sentiment analysis,” in Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies, (Portland, Oregon, USA), pp. 142–150, Association for Computational Linguistics, June 2011.
[2] The 23rd Annual Conference of the Language Processing Society of Japan (NLP2017), 2009.
[3] W. Yin, K. Kann, M. Yu, and H. Sch¨utze, “Comparative study of CNN and RNN for natural language processing,” CoRR, vol. abs/1702.01923, 2017.
