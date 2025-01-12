# English-to-French Translation Model

This repository contains a project focused on building an English-to-French translation model using an encoder-decoder architecture with Long Short-Term Memory (LSTM) networks. The project explores the challenges faced by such models and highlights the importance of the attention mechanism in sequence-to-sequence (seq2seq) translation tasks.

## Overview

The model employs:
- **Encoder-Decoder Architecture**: Utilizes LSTMs for both encoding the input sequence and decoding to produce the output sequence.
- **Teacher Forcing**: Implements teacher forcing during training to improve convergence.

This implementation does **not** include the attention mechanism, deliberately showcasing the limitations of traditional LSTM-based encoder-decoder architectures. A comparison with attention-based approaches is available in the `latex` folder.

## Features
- Translate English sentences into French using LSTM-based seq2seq models.
- Explore challenges in translation tasks without attention mechanisms.
- Analyze performance differences with and without attention mechanisms.

## Getting Started

To run this Project Locally, clone the repo and then install the requirements, after that run the website.py file 

## Resources 
- **Explanation of the Model**: Watch the unlisted YouTube video for a detailed explanation of the model and its design decisions.<a href="https://youtu.be/I_LDBGqHpfU?si=fm9CsyYSlVq4o76U" target="_blank">Watch Video</a> <!-- [Watch Video](https://youtu.be/I_LDBGqHpfU?si=fm9CsyYSlVq4o76U) -->
- **Comparison with Attention Mechanism**: Refer to the latex folder for a comprehensive comparison of the performance and limitations of the LSTM-based model versus models incorporating attention mechanisms.

## About 
This project was developed to showcase the limitations of LSTM-based encoder-decoder architectures and the importance of attention mechanisms in seq2seq tasks.
