# corn-seed-image-classification

# Author
Sakdipat Ontoum

https://www.linkedin.com/in/sakdipat-ontoum-256bb0209/

# Introduction

![](https://media.istockphoto.com/photos/closeup-of-organic-yellow-corn-seed-or-maize-fullframe-background-picture-id1308275817)

Corn is one of the plants that produce high-quality feed at a reasonable cost. It has many appearances and is a significant factor that one may use in society for us as humans in terms of food that we eat as well as a source of feed for cattle. Sometimes, if we deeply analyze the structure of corn, especially corn seeds. There are many categories such as pure, broken, discolored, and silkcut, which people cannot be classified with the naked eye. Therefore, machine learning specialists are approached and charged with developing machine learning model that can distinguish between photos taken in those four categories.

# Objective

This aim is to create a model that can predict whether a photograph was shot in front of a corn seed correctly - a multiclass image classification challenge.

# Approach

This machine learning project is divided into two parts which are Model development and data mining. Model deployment and operationalization will not be discussed because this model will not be put to production until later.

The training dataset will be utilzed from [It's Corn (PogChamps #3)](https://www.kaggle.com/competitions/kaggle-pog-series-s01e03) competition. The train image, it is consist of png file around 14.3k files. 

Second, the training dataset has a pretty large size, a Fastai  will be utilized to tackle this task. The Fastai is deep a deep learning library that provides practitioners with high-level components that can rapidly and easily give state-of-the-art results in traditional deep learning domains, but they require specialized hardware to process the information, such as a Graphical Processing Unit (GPU) as well.


# Dataset

The datadet either training or testing set, will be e utilzed from [It's Corn (PogChamps #3)](https://www.kaggle.com/competitions/kaggle-pog-series-s01e03) competition. There is contain images of corn that can be classified in one of four catgories such as pure, broken, silkcut, and discolored. 

# Performance Measure

The model will be improved and tested for F1-score.
