# Twitter_NLP_analysis

<<<<<<< HEAD
#### Authors: Raul Torres Ziyuan Terry

### Overview

In this Twitter sentiment analysis project, we analyzed over 9,000 data points from Apple and Google, with positive, negative, and neutral responses. This was a supervised machine learning algorithm, where the training data was labeled with the correct sentiment (positive, negative, or neutral) for each tweet. The algorithm then learned from this training data to make predictions on the sentiment of new, unseen tweets. The results of the analysis showed that the majority of tweets about both Apple and Google were positive in sentiment, with a smaller percentage of negative and neutral tweets. This analysis provided valuable insights into public opinion about these two tech companies.


### Business Problem 

Apple is interested in understanding how the public views the company and its products. In order to improve its marketing and public relation strategies, Apple has decided to conduct a Twitter sentiment analysis project to gather insights into public opinion. The project involves analyzing over 9,000 tweets about Apple and its products, using a supervised machine learning algorithm to classify the tweets as positive, negative, or neutral in sentiment. The results of the analysis will provide valuable information about the overall sentiment towards Apple, as well as specific areas where the company may need to improve in order to better align with public opinion. This information will be used to inform future marketing and public relation strategies for the company.


### Methods 

In this Twitter sentiment analysis project, our method was binary, meaning that we classified the tweets into two categories: positive or negative. We did not include a neutral category in our analysis. The algorithm was trained on a labeled dataset of tweets, where the sentiment of each tweet was manually labeled as positive or negative. The algorithm then learned from this training data to make predictions on the sentiment of new, unseen tweets. 
In addition to this, it is worth mentioning that the tweets in the dataset were preprocessed using natural language processing (NLP) techniques to clean and prepare the data for training. These techniques  include removing stop words, stemming or lemmatizing words, and other methods to make the data more easily understandable by the algorithm as it allows the algorithm to focus on the most important aspects of the text.
The results of the analysis showed that the majority of tweets about both Apple and Google were positive in sentiment, with a smaller percentage of negative tweets. Since we decided to use Apple as our main stake holder we decided to filter out the data to just show positive and negative results for Apple. 
This is how the data looked like:

***ADD A GRAPH***



### Results 





### Conclusion
As a conclusion to this Twitter sentiment analysis project, it is worth noting that our natural language processing (NLP) model achieved an accuracy of 88.5% in classifying the sentiment of tweets as positive or negative. This high accuracy is a testament to the effectiveness of our machine learning algorithm, which combined decision tree learning and naive Bayes classification to make predictions. Overall, the results of the analysis showed that the majority of tweets about both Apple and Google were positive in sentiment, with a smaller percentage of negative tweets. This suggests that overall, people tend to have a positive sentiment towards these two companies and specially Apple. In conclusion, using NLP techniques in combination with machine learning can provide valuable insights into the sentiment of tweets about a particular topic or company.

=======
**Authors**:  Ziyuan Wang, Raul Torres

## Overview




## Business Problem




## Data





## Methods



## Results
![graph1](./images/Picture1.png)




![graph2](./images/Picture2.png)

We found out that the accuracy score is 83.577 for the baseline model. The best score for final model is 88.500 which was not a big improvement from the original data but it’s a pretty solid number closed to 90%.

![graph3](./images/Picture3.png)

The accurate prediction for positive emotion was great, but the model didn’t have a good performance with the negative emotion. The size of the dataset was one big reason for this. There are over 9000 rows for the original dataset but after we drop nans and filter row with only positive and negative emotions, only 3000 rows left. The model could have a better performance with more data points.

## Limitation and Future plan

![graph4](./images/Picture3.png)

For the limitation, the biggest limitation would be data point as I mentioned. Something about the original data was not that good so We create a function trying to find product category better and only have 1348 nans which is 4000 nans less compared with the original dataset. Another limitation would be the percentage of positive emotion is very high shown from the previous slides. So, in the future with more time and money, we want to add more datapoints and continue refining the model. Maybe trying multi class model with neutral emotion to make our model more powerful.

## Conclusions

In conclusion, our model had a solid performance about predicting the emotion from a tweet. By using our model, Apple marking department could instantly find out the thoughts from people about specific product like ipad or iphone. And then they can decide if are going to Increase production on products who with more positive emotion. Or maybe contact technical department to make improvement on products with more negative emotion.



## For More Information

Please review our full analysis in [our Jupyter Notebook](./Pump-it-Up-Data-Mining-the-Water-Table_Final_Notebook.ipynb) or our [presentation](./Pump-it-Up-Data-Mining-the-Water-Table_Presentation).

For any additional questions, please contact **Ziyuan Wang & zywang1994@gmail.com, Raul Torres & cassielponce@icloud.com**

## Repository Structure

```
├── README.md                                                     <- The top-level README for reviewers of this project
├── .ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── .pdf       <- PDF version of project presentation
└── images                                                        <- images folder used for project
└── Data                                                          <- data folder used for this project
└── Scratch_code                                                  <- Processed_notebook folder used for this project
```
>>>>>>> 3552b24ecd7f38439c350ce72fe59d4dbf7230a2
