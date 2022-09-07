# (Not so) Deep Chatbot

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#purpose-of-project">Purpose of Project</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#architecture">Architecture</a></li>
    <li><a href="#technologies">Technologies</a></li>
    <li><a href="#how-to-run">How to run</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## Purpose of Project

* Train a model to answer customer of a cafe
* Learn the very basic of NLP

## About

This is a chatbot of a cafe (for now only chat on command promt)

## Architecture

* A shallow network with 1 input layer, 2 hidden layer (each have 8 node), 1 softmax layer

## Technologies

* Language: Python
* Framework: PyTorch

## How to run

### Prerequisites

Required Libraries:
* pytorch
* numpy
* nltk

### Data preparation

Make sure everything is set in `intents.py` file.

### Download `punkt`

On your command promt, run `python`, then run `nltk.download('punkt')`

### To train the model
```
python train.py
```

### To chat
```
python chat.py
```

## Acknowledgments

* Youtube Tutorial: [video](https://youtube.com/playlist?list=PLqnslRFeH2UrFW4AUgn-eY37qOAWQpJyg)
