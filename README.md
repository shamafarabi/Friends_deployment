# Deploying NLP Model for Prediciting Cast Member in the TV show "Friends"(https://render.com)

This is a deployment of a multiclass text classification web app I developled using fastai. A user can input any line he\she wants from the transcripts of the tv show "Friends" and let the ML model guess the character. You can play with it [here.](https://friends-2b3s.onrender.com/)


The data for this ML modeling was scraped from trasncripts available online.  An RNN based AWD LSTM Model pretrained on WikiTxt dataset was used as a language model and then fine tuned with the dataset for this project. The language model was then trained for building the classification model. 
