# music-genre-classifier
A repository containing a machine learning algorithm that is trained to identify a song's genre using the song's audio file as input. 

## Project Background:
I am using this project as an opportunity to apply the teachings of the two ML certifications I took from DeepLearning.AI. I am a big fan of music and as such felt that it would be personally interesting to apply ML to music in some way. I decided on an idea to create a project that would allow a user to submit an audio file of a song, and in return the program would spit out a prediction of what it thinks music genre is. Upon further reading, I discovered that in 2002 a group of researchers attempted to create a music classifier [link](https://ieeexplore.ieee.org/document/1021072) and achieved an accuracy of 65%, so that was the benchmark to beat. I also wanted this project to contain updated music genres that matched current listening trends, and so after doing research about top streaming genres I settled on the following ten genres:
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
* TensorFlow model file
* Training Dataset
* GUI file for interacting with the model and submitting songs
* Dockerfile for containing/running all dependencies
