# Data science blog for Udacity Data Scientist Nanodegree Project

Blog published at this [link](https://medium.com/@kndtran/australia-vs-usa-compensation-for-software-engineers-and-the-growth-of-programming-languages-31b1cbae1b2f).

In summary, I investigated the differences in the compensation for software engineers between Australia and the US, and the change in the usage of programming languages, in the last 5 years. There is a large gap in compensation with the US having much higher compensation. The programming language Rust has seen the largest percentage growth in the last 5 years.


## 0. Setup and Installation

In the folder of this project, follow these steps:

1. (Optional but recommended) Create a Python virtual environment
  - `python3 -m venv venv`  then `source venv/bin/activate`
2. Install the required packages
  - `pip install -r requirements.txt`
3. Start Jupyter notebook
  - `jupyter-lab`
4. Open the `stackoverflow-analysis.ipynb`

Important files in this repo:
- `stackoverflow-analysis.ipynb` - Jupyter notebook with the code for the published blog
- `requirements.txt` - file containing the Python libraries needed to run the notebook
- `README.md` - this README file
- `data/` folder - this will be created by the notebook to store the downloaded StackOverflow survey data


## 1. Business Understanding

I grew up in Australia and later immigrated to the USA. I wanted to see how the compensation differs for software developers in Australia and in the USA, and the changes in the programming languages used by software developers.

I chose this project because I heard a lot of anecdotal stories from my friends in the US about how much higher the compensation is and that I should relocate. I have since relocated and the compensation does feel higher, but I did not have quantitative evidence. We have also talked about learning the new programming languages as a potential change in career.

Thus, I investigated the trends over the last 5 years, addressing the following specific questions:
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


## Acknowledgments

- Udacity [Data Science for Scientists](https://learn.udacity.com/nanodegrees/nd001-ibm-datascience) nanodegree and the mentors and reviewers for giving help and feedback.
