# Project: Natural Language Processing with Disaster Tweets

## Objective:
To build a machine learning model that can predict whether a given tweet is about a real disaster (target=1) or not (target=0).

## Methodology:

We will use a Long Short-Term Memory (LSTM) network, with pretrained embedding layer with unfrozen weights

### improving results:

Tried 2 improved architechtures:
1. adding a conv layer: pretrained embeddings + conv layer + LSTM layer
2. adding attention layer: pretrained embeddings + LSTM layer + attention Layer

Both yeilded better closely matched performance the better model was selected to predict on unseen data and the results were uploaded to kaggle
