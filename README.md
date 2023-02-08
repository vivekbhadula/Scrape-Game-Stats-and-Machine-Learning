# Scrape-Game-Stats-and-Machine-Learning

This is my group project assignment, in which me and Tharun are tackling the problem of smurfing in the game 'Valorant'. 

Smurfing is increasingly becoming a problem in gaming. Smurfing happens when experienced players make new low-level accounts in order to play competitive modes against lower-ranked players. This ruins the gaming experience for legit new players because they are immediately matched with highly skilled smurf accounts. 

The data was collected from the website ‘https://tracker.gg/valorant/lfg’, this is one of the most used and highly recognised trackers in the industry and has been approved by the developers of Valorant. The different game statistics were extracted from the website using a web scraper.

The prediction of the rank of a player is a classification model according to the problem statement but we have still implemented different types of techniques to learn from their outputs for how we could get better results. All models were implemented in a Google Colaboratory, using the scikit-learn library for python.

We predict the estimated rank of a player using Lasso Regression, Ridge Regression, kNN and SVM.
