# Simple Real-time Maths Recognition - a digit recognition ML project
This project was done as a personal project for the purpose of applying CNN knowledge.

#### -- Project Status: Completed November 2019

## Project Intro
Taking another step from the famous MNIST hand-written digit recognition problem, this project aims to recognize hand-written digits and simple maths operations (addition and multiplication). Inspired by CNN models by [Singh](https://medium.com/@ayrusreev/real-time-digit-recognition-using-keras-5f333c0163e2) and [Vipul](https://github.com/vipul79321/Handwritten-Equation-Solver), I trained 2 simple models on a small non-MNIST dataset (with "+" and "x" characters) to recognize the aforementioned characters and built a simple PyGame to recognize and evaluate real-time input.

## PyGame Control
* Choose a model `vipul_model'` or `'suryaveer_model'` in `predict_digit` function
* Write input continuously in the left canvas
* Press 'Enter' to evaluate in `stdout`
* Left click to reset canvas
* Press 'Esc' to close

## Demo
![Demo](https://github.com/danieltpham/real-time-maths-recognition/blob/master/demonstration.gif)
![Demo Result](https://github.com/danieltpham/real-time-maths-recognition/blob/master/demonstration_result.JPG)

## Methodologies
* Python, Keras, PyGame
* CNN

## How To Test
* Download `master_maths_recognition.ipynb` and run with training dataset from [here](https://github.com/vipul79321/Handwritten-Equation-Solver/blob/master/train_final.csv)

## Limitation
Testing on MNIST dataset yields a 0.2145 accuracy score, which shows weaknesses in the models & input processing pipeline.
