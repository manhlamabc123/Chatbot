# (Almost) Deep Chatbot

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
* nlkt

### Data preparation

Make sure everything is set in `intents.py` file.

### To train the model
```
python train.py
```

### To chat
```
python chat.py
```

## Acknowledgments

* Youtube Tutorial: [video](https://www.youtube.com/watch?v=yN7qfBhfGqs)
* How to Implement Spatial Transformer Network in PyTorch: [doc](https://pytorch.org/tutorials/intermediate/spatial_transformer_tutorial.html)
