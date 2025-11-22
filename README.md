# Sign-Language-Conversion
## Table of Contents

- [Aim](#aim)
- [Abstract](#abstract)
-  [Project Overview](#project-overview)
-  [Features](#features)



## Aim

This project aims to create a sign language translator using machine learning techniques and Python programming. The application utilizes various modules, primarily Mediapipe, Landmark, and Random Forest algorithms to interpret and translate sign language gestures into text or spoken language.

## Abstract

Sign language is one of the oldest and most natural form of language for communication, but since most people do not know sign language and interpreters are very difficult to come by we have come up with a real time method using neural networks for fingerspelling based american sign language.
 
In this method, the hand is first passed through a filter and after the filter is applied the hand is passed through a classifier which predicts the class of the hand gestures. This method provides 98.00 % accuracy for the 26 letters of the alphabet.


## Project Overview
Sign language is a crucial form of communication for individuals with hearing impairments. This project focuses on bridging the communication gap by creating a tool that can interpret sign language gestures in real-time and convert them into understandable text or speech.

This project leverages Flask for the web interface and TensorFlow/Keras for the machine learning model to recognize sign language gestures in real-time from a webcam feed.

## Features
* **Real-time sign language recognition**: Captures hand gestures using the Mediapipe library to track landmarks and movements.
* **Landmark analysis**: Utilizes Landmark module to extract key points and gestures from hand movements.
* **Machine learning translation**: Employs Random Forest algorithm to classify and interpret gestures into corresponding text.
* **Text-to-speech**: For better communication the text can be converted to spoken language using the speech synthesis.
## Architecture Diagram

<img width="610" height="666" alt="image" src="https://github.com/user-attachments/assets/a585174b-5444-43cf-9236-393576083cc0" />

## Demo

<img width="733" height="584" alt="image" src="https://github.com/user-attachments/assets/eaae8275-7b89-40e4-b5f9-58d9deb98fcf" />

![slc](https://github.com/user-attachments/assets/1a904f18-4f69-4d83-bf79-90acdf940af7)

