# meme-category-cnn-classifier
TLDR: This is an interactive machine learning model that is trained to identify a meme's category using the image itself as input. 

## Project Background:

This project is an opportunity to apply the teachings of the two DeepLearning.AI certificates I recieved in TensorFlow and MLOps. Memes have been a large part of my presence on the internet and social media. As someone who has always appreciated and participated in various forms of comedy, I wanted this project to involve some aspect of my life that I enjoy. I began looking at memes starting in 6th grade back in 2011, and as I got older I became fascinated by the ways in which memes evolve over time. The type of jokes, the image formats, degrees of irony, etc. all evolve over time as people's internet humor preferences evolve. I have always wanted to create methods of grouping memes; so for this project I am attempting to use machine learning to label memes into the year that they were created. Using training data, I will train the model on memes ranging from 2010-2022, with the meme itself as input and the year it was made being the output label. After training, the finshed model should be able to take a meme as input, and using a softmax output function, predict what year the meme was created. This may work out terribly, but I can't know for sure until I try it. So, this repository will store the GUI, API, Dockerfile, and finished model for users to upload their own memes, and recieve a predicted year in response. Any updates or progess on the model will be written in this readme.md. 



## Repository Elements:
This repository will contain the following elements:
* **memeEraML.py** : main file for interacting with the model API and submitting memes through a GUI 
* **Dockerfile** : Dockerfile for containing/running all dependencies

## Instructions for Use:


## Model Components/Details:
