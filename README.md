# meme-category-cnn-classifier
TLDR: This is an interactive machine learning model that is trained to identify a meme's category using the image itself as input. 

## Project Background:

This project is an opportunity to apply the teachings of the two DeepLearning.AI certificates I recieved in TensorFlow and MLOps. Memes have been a large part of my presence on the internet and social media. As someone who has always appreciated and participated in various forms of comedy, I wanted this project to involve some aspect of my life that I enjoy. I began looking at memes starting in 6th grade back in 2011, and as I got older I became fascinated by the ways in which memes evolve over time. The type of jokes, the image formats, degrees of irony, etc. all evolve over time as people's internet humor preferences evolve. I have always wanted to create methods of grouping memes; so for this project I am attempting to use machine learning to label memes into the year that they were created. Using training data, I will train the model on memes from eight different categories/genres. These categories are by no means exhaustive, and certainly not mutually exclusive. I have tried to create 8 different categories that are distinct enough for a CNN to pick up its visual traits in the training set, and vague enough that I do not have to find memes for hundreds of subgenres. The goal was to have a sweet spot of a few genres that could describe a significant majority of internet memes, each genre having its own unique attributes. These categories may change over time, and I may in the future create a crawler that would be able to scrape thousands of images, in which case I could have more genres and likely a more accurate model due to a larger training set. 

## Meme Categories:
* 1. **Rage Comics**: These were some of the first internet memes; also posses a very distinct visual style, perfect for classification. 
* 2. **Top-Text/Bottom-Text**: This is the original "meme" format of a specfic character with the top text presenting a setup, and the bottom text being the punchline. Also almost always uses a particular font, which is also good for classification. 
* 3. **Text Post**: This genre is easily the most widely shared genre of meme, and this genre is what largely brought memes into mainstream culture. The definition of "meme" is fluid here, since in some text posts there is no subversion/replication of a prior joke, but rather just a funny social media post that is typically cropped and reposted. Sometimes an image accompanies the text, but I tried to focus on memes where the focus is around the text post itself, typically from twitter, tumblr, or facebook.  
* 4. **Ironic/Surrealist**: Here is where the genres begin to get complicated. An ironic memes is any meme that is either ironically engaging with the source material, and/or has visually distorted the meme in a way to convey sarcasm (*or for for the sole comedic value of visual distortion*.) I have also lumped surreal memes into this category, which stylistically are similar to ironic memes, but typically have an even greater detachment from the original meme. Surreal memes also tend to lack a primary sense of logic and coherence, disregarding standard conventions of joke setups and punchlines for a series of letters, words, or phrases that have little to no connected meaning. 
* 5. **Post-Ironic**: Post-ironic memes are ones that (as you would have guessed), go beyond the subversion of irony. This can be expressed through either a return to pre-irony (also known as "earnest truth"), or meta-irony (muddying the ironic and non-ironic into ambiguity.) So, if a meme contains text that is earnestly descriptive, or is an obfuscating mix of sincerity and irony, that meme would be considered post-ironic. This genre was created after the era of ironc memes, and are very popular in contemporary internet culture. 
* 6. **Viral Video**: This genre is a screenshot or thumbnail from a viral video, typically from youtube. The model can only take in pictures as input, so while it cannot be fed video footage, I am including this category with thumbnails of viral youtube videos to see if the model can pick up on the visual atttributes that come from video thumbnails (e.g. low quality, play/pause button, youtube logo, watermark, etc.) 
* 7. **Political Memes**: This genre is for any memes that discuss or reference political events, politicians, or political institutions. Due to many political memes being about the same few politicians (e.g. Trump, Biden, AOC) and most political campaigns creating memes from the same few formats, I am including this category to see if the model can pick up on the commonalities of political memes. 
* 8. **Experimental**: This genre is sort of the "else" category in an "if-else" statement. Since the definiton of what a meme can be is always evolving and becoming more abstract, it is arguable that any image *can* be a meme, it just might not be a meme that is particularly popular just yet. So, this genre is any random image with absolutely no common traits or attributes other than that these images do not fit into any other category. So, an experimental meme is one that pushes the boundaries of what a meme is, and what it can look like.





## Repository Elements:
This repository will contain the following elements:
* **memeEraML.py** : main file for interacting with the model API and submitting memes through a GUI 
* **Dockerfile** : Dockerfile for containing/running all dependencies

## Instructions for Use:


## Model Components/Details:
