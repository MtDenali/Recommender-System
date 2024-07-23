# Project Title

Recommender system using movie dataset

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)

## Project Description

The increasing importance of the web as a medium for electronic and business transactions and advertisement, and social media has served as a driving force behind the development of recommender systems technology. Among the benefits, recommender systems provide a means to prioritize data for each user from the infinite information available on the internet. Such systems are critical to ensuring (among others): (a) the detection of hate speech, (b) user retention on a web service, and (c) fast and high-quality access to relevant information. An important catalyst is the ease with which the web enables users to provide feedback about a small portion of the web that they traverse.

Such user-driven sparse feedback poses the following challenge in the desing of recommender systems: Can we utilize these sparse user datapoints to infer generalized user interests?
We define some terms:

• The entity to which the recommendation is provided is referred to as the user; 

• The product being recommended is an item.

The basic models for recommender systems works with two kinds of data:

A **User-Item** interactions such as ratings (a user (you) provides ratings about a movie (item));

B **Attribute** information about the users and items such as textual profiles or relevant key- words (deep representations about a user or item).

Models that use type A data are referred to as **collaborative filtering methods**, whereas models that use type B data are referred to as **content-based methods**. In this project, we will build a recommendation system using collaborative filtering methods.


**Collaborative filtering models** use the collaborative power of established user-item interactions to make recommendations about new user-item interactions. In this project we use a ratings database where the user is an audience member who viewed a movie, and the item is the movie being rated.
The main challenge in designing collaborative filtering methods is that the underlying ratings matrices are **sparse**. Consider this example of a movie application in which users specify ratings indicating their like or dislike of specific movies. Most users would have viewed only a small fraction of the large universe of available movies and as a result most of the ratings are unspecified.

The basic idea in neighborhood-based methods is to use either **user-user** similarity or **item-item** similarity to make predictions from a ratings matrix. There are two basic principles used in neighborhood-based models: user-based or item-based. In this project, we will only implement user-based collaborative filtering.

 **User-based models**: Similar users have similar ratings on the same item. Therefore, if John and Molly have rated movies in a similar way in the past, then one can use John’s observed ratings on the movie Terminator to predict Molly’s rating on this movie. Item is kept constant.

  Then, we shift our focus to how __ranking approaches__ enhance recommendation systems by not only identifying relevant items but also prioritizing them for optimal user satisfaction and engagement.
Next, we’ll demonstrate the learning-to-rank concept using LightGBM(Light Gradi- ent Boosting Machine) with LambdaRank, a pairwise approach, applied to the Microsoft Learning to Rank (MSLR-WEB10K) dataset.

## Features
- Feature 1: colab_filter_movie.ipynb uses user-based collaborative filtering to implement recommender for movie dataset.
- Feature 2: learn_to_rank_web10k.ipynb uses learn-to-rank concept for Web-10k dataset.

## Installation

Not required.




