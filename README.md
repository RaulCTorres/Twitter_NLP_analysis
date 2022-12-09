# Twitter_NLP_analysis

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
