# music-genre-classifier
TLDR: A repository containing a machine learning algorithm that is trained to identify a song's genre using the song's audio file as input. 

## Project Background:
I am using this project as an opportunity to apply the teachings of the two ML certifications I took from DeepLearning.AI. I am a big fan of music and as such felt that it would be personally interesting to apply ML to music in some way. I decided on an idea to create a project that would allow a user to submit an audio file of a song, and in return the program would spit out a prediction of what music genre it thinks it is. Upon further reading, I discovered that in 2002 a group of researchers attempted to create a music classifier ([link](https://ieeexplore.ieee.org/document/1021072)) and achieved an accuracy of 65%, so that was the benchmark to beat. A lot has progressed in AI since the paper was written, and so I wanted to build my own genre classifier using my own dataset, building a model from scratch, and doing all of the model tuning and pipeline building. I have built many predictive models with structured datasets, images, and text, but never audio files, so learning how to process audio for AI would be an interesting challenge for me. I also wanted this project to contain updated music genres that matched current listening trends, and so after doing research about top streaming genres I settled on the following ten genres:
* Pop
* Hip-Hop/Rap
* Electronic/EDM
* Rock
* R&B
* Latin
* K-Pop
* Country
* Classical
* Metal

## Repository Elements:
This repository will contain the following elements:
* **musicGenreML.py** : main file for interacting with the model API and submitting songs through a GUI 
* **Dockerfile** : Dockerfile for containing/running all dependencies

## Instructions for Use:
