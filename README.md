# Text_Classification &middot;
> The program follows a similar structure as one demonstrated in fastai courses


We shall use a pre-trained network which at least knows how to read English. 
We will train a model that predicts a next word of a sentence (i.e. language model), and just like in computer vision, stick some new layers on the end and ask it to predict whether something is positive or negative


Fine-tuning a pre-trained network is really powerful.
If we can get it to learn some related tasks first, then we can use all that information to try and help it on the second task.
After reading a thousands words knowing nothing about how English is structured or concept of a word or punctuation, all you get is a 1 or a 0 (positive or negative).
Trying to learn the entire structure of English and then how it expresses positive and negative sentiments from a single number is just too much to expect.

## Installing / Getting started

You need to use fastai 0.7; please follow the installation instructions [here](https://forums.fast.ai/t/fastai-v0-install-issues-thread/24652)  .


## Developing

### Built With
fastai 0.7, sklearn, spacy libraries

### Prerequisites
What is needed to set up the dev environment. For instance, global dependencies or any other tools. include download links.
NVidia GPU with programming framework CUDA is helpful for training and testing the models

### Setting up Dev

Here's a brief intro about what a developer must do in order to start developing
the project further:

Set the PATH variable to your relavant folder location
```shell
git clone https://github.com/anandpuntambekar/Text_Classification.git
cd Text_Classification/
```


## Style guide

The notebook is well commented explaining in technical details each and every step of the process end to end. This includes tokentization, word embedding, data exploration, Language Model Development, Sentiment Clasification,testing and analysing the results

## Database
The data for the project is the famous IMDB data set and can be downloaded from [https://www.kaggle.com/iarunava/imdb-movie-reviews-dataset]

