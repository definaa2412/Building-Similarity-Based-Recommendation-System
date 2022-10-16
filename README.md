# Mini Project - Building Similarity Based Recommendation System
Defina Ambarwati : [Github](https://github.com/definaa2412)
***

## Introduction

<p align="justify"> A recommendation system is a system that generates a list of items or products for users as a recommendation based on various factors. One of the methods on the recommendation system is <strong>Collaborative Filtering</strong>. Collaborative filtering is a technique that can filter out items that a user might like on the basis of reactions by similar users. It works by searching a large group of people and finding a smaller set of users with tastes similar to a particular user. It looks at the items they like and combines them to create a ranked list of suggestions. </p>

## Dataset

<p align="justify">
  
Dataset used consists of 100004 raws of users and four columns such as **userId**, **movieId**, **rating** and **timestamp**. This data is provided by [Coursera](https://www.coursera.org/projects/building-similarity-based-recommendation-system).
  
</p>

## Goals
1. Apply collaborative filtering concept to build a recommendation system.
2. To filter and predict only those movies that a corresponding user is most likely to want to watch.

## Summary
### Data Preprocessing
&nbsp;&nbsp;&nbsp;&nbsp; Check the missing values.

### Data Preparation
1. Create user item matrix (interaction matrix) with pivot.
2. Create a function to find the most similar users on the basis of cosine similarity.
