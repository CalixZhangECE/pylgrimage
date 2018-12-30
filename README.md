# pylgrimage
Project for the University of Toronto Data Science Team

## Problem: 
Using collaborative filtering for customer segmentation. Given a set of users and locations that they have visited (i.e checked in), I would like to find recommendations for new locations for each user. Further I would like to cluster users into groups based on locations they have visited; Also find similar locations based on visitor patterns.

## Data:
Gowalla (acquired by Facebook) is a location-based social networking website where users share their locations by checking-in. We have collected a total of 6,442,890 check-ins of these users over the period of Feb. 2009 -Oct. 2010. (See here https://snap.stanford.edu/data/loc-Gowalla.html)

## Challenges 
Unlike traditional recommendation systems like movie ratings, we only have the data of whether a user visited a location or not (i.e binary). We do not have any other information (ex. type, name) about the locations other than a unique identifier of the location.
