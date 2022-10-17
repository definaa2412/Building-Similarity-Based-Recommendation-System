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
<p align = "left">
Check the missing values.
</p>

### Data Exploration
1. Total Movies and Total User
   
<div align="center">
  <table>
    <tr>
      <td align="center"> <strong>Total Movies</strong> </td>
      <td align="center"> <strong>Total Users</strong> </td>
    </tr>
    <tr>
      <td align="center"> 9066 </td>
      <td align="center"> 671 </td>
    </tr>
  </table>
</div>

2. Top 10 Movies with the Most Rating & Top 10 Users give the Most Rating
   
   ![10movie](https://github.com/definaa2412/Building-Similarity-Based-Recommendation-System/blob/main/images/top%2010%20movies.png)
   ![10user](https://github.com/definaa2412/Building-Similarity-Based-Recommendation-System/blob/main/images/top%2010%20users.png)
   
      
### Data Preparation
<p align = "left">
Create user item matrix (interaction matrix) with pivot.
</p>

<div align ="center">
  
![im](https://github.com/definaa2412/Building-Similarity-Based-Recommendation-System/blob/main/images/interaction%20matrix.png)
  
</div>

### Build the Sistem
1. Create a function to find the most similar users on the basis of cosine similarity.
2. Create a **recommendation** function to recommend the movie based on collaborative recommendation system.

### Test the Function
We'll test the recommendation function applied to user id 564 and the result as following:

![testfunction](https://github.com/definaa2412/Building-Similarity-Based-Recommendation-System/blob/main/images/function%20test.png)

5 Movies ID are recommended to User ID 564 are 1537, 515, 1027, 2565 and 524.

## Conclusion
Our self-build function success to recommend the movie. It's pretty simple but it's such a good learning about recommendation system. Thank you.


