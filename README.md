# Data science blog for Udacity Data Scientist Nanodegree Project

Blog published at this [link](https://medium.com/@kndtran/australia-vs-usa-compensation-for-software-engineers-and-the-growth-of-programming-languages-31b1cbae1b2f).

## 1. Business Understanding

I grew up in Australia and later immigrated to the USA. I wanted to see how the compensation differs for software developers in Australia and in the USA, and the changes in the programming languages used by software developers.

I investigated the trends over the last 5 years, addressing the following specific questions:
1. Which country has the highest compensation?
2. What was the compensation growth based on professional experience?
3. Which programming languages have had the most positive change in the last 5 years?

## 2. Data

I downloaded the StackOverflow data from 2019 to 2023 and processed the data to have the required features to answer the questions above. I investigated the data over the different years to find the relevant features. For these features, I cleaned up the feature names and feature values to be consistent over the different years and then selected the relevant features to answer the questions above.

## 3. Analysis and Visualization

In answering the three questions above, I added code to convert the data to right shape and filtered out the values for plotting.

I experimented with a few different styles of plots using `matplotlib`, but kept the ones for the blog in the code.

## 4. Results

The answers to the questions above:
1. Which country has the highest compensation? USA
2. What was the compensation growth based on professional experience? USA
3. Which programming languages have had the most positive change in the last 5 years? Rust
