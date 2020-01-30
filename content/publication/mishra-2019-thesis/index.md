---
title: "Linking Models for Collective Attention in Social Media"
date: 2019-01-01
publishDate: 2019-12-29T23:55:04.471320Z
authors: ["Swapnil Mishra"]
publication_types: ["7"]
abstract: "Social networks are ubiquitous in the modern world for propagating and acquiring information. Thus, understanding and predicting the popularity of online information is an important problem in social media analysis. Considerable progress has been made recently in data-driven predictions, and in linking popularity to various external factors. Most of the work on popularity prediction and understanding is either based on learning a variety of features from full network data or using generative processes to model the event time data. However, there exists no prior work that connects or compares models across different paradigms. Accordingly, this thesis focuses on developing and connecting models to predict and understand popularity across different paradigms and settings. To this aim, we first bridge gaps between feature-driven and generative models with the help of a hybrid model and a new performance benchmark. We model each social diffusion with a marked Hawkes self-exciting point process, and we estimate from data the content virality, memory decay, and user influence. Next, we learn a predictive layer for popularity prediction using a collection of cascade histories. We show the Hawkes process with a predictive overlay outperforms recent feature-driven and generative approaches on both existing tweets data and our new dataset. We also show that a feature-driven method based on a basic set of user features and event time summary statistics performs competitively in both classification and regression tasks and that adding point process information to the feature set further improves predictions. A common benchmark dataset for popularity prediction helps us to utilize both feature-driven, and generative paradigms to better predict and understand online popularity. As the first proposed work that links models across feature-driven and generative models, our work has influenced subsequent works on online popularity since its publication in 2016. Secondly, we identify that the existing methods for popularity modeling and prediction typically focus on a single source of external influence. However, for many types of online content such as YouTube videos or news articles, attention is driven by multiple heterogeneous sources simultaneously - e.g., microblogs and traditional media coverage. Correspondingly, we propose RNN-MAS, a recurrent neural network for modeling asynchronous streams. It is a sequence generator that connects multiple streams of different granularity via joint inference. We show that RNN-MAS not only outperforms the current state-of-the-art YouTube popularity prediction system, but it also captures complex dynamics, such as the seasonal trends of unseen influence. Further, to increase the explainability and interpretability of our model, we propose two new metrics: the emphpromotionresponse quantifies the gain in popularity from one unit of promotion for a YouTube video; the emphloudness level captures the effects of a particular user tweeting about the video. We use the loudness level to compare the effects of a video being promoted by a single highly-followed user (in the top $1%$ most followed users) against the same video being promoted by a group of mid-followed users. We show that results depend on the type of content being promoted: superusers are more successful in promoting Howto and Gaming videos, whereas the cohort of regular users is more influential for Activism videos. Additionally, we apply the RNN-MAS model to the problem of predicting the popularity of an item before being published. We train a single model for a group of videos to learn possible evolution dynamics of a given video from the historical data of the videos in the same group. A novel simulation strategy based on the proposed metrics enables us to simulate a representative promotion for the video, and predict the achieved popularity before it is published. Experiments on our large scale YouTube dataset show that our proposed method outperforms non-trivial baselines. By and large, this thesis proposes models for popularity modeling and prediction that are the first of their kind, and it links models across various paradigms and data availability. This work provides accurate and explainable popularity predictions, as well as computational tools for content producers and marketers to allocate resources for promotion campaigns. In addition to these contributions, this work may contribute to a more comprehensive understanding of popularity prediction and understanding models across different classes or types."
featured: false
publication: "*The Australian National University*"
url_pdf: "https://openresearch-repository.anu.edu.au/handle/1885/182586"
---
