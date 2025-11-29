# Bot Bidders Detector 🕵️‍♀️🤖

Predict whether an online auction bid was placed by a human or an automated bot using deep learning.

This project explores how user bidding behaviour in online auctions can be modeled to distinguish real human bidders from bots. This was presented by Facebook on Kaggle (https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot), which focuses on predicting if a bid is made by a human or a bot in large-scale bidding logs.  

## Project Overview

Online auction platforms are often targeted by automated bots that place bids in an unnatural way.  
The goal of this project is to:

- Analyse bidding behaviour from historical logs  
- Engineer meaningful behavioural features per bidder  
- Train a deep learning classifier to detect bot bidders  
- Evaluate model performance and visualise the results  

The main work is done inside Jupyter notebooks.

## Models Used
This project implements and compares three deep learning approaches:
- **MLP (Multi-Layer Perceptron)** – processes statistical and aggregated behavioural features.
- **LSTM (Long Short-Term Memory)** – learns temporal bidding patterns from sequential bid data.
- **Hybrid MLP-LSTM Model** – combines both statistical features and sequential features for improved performance.
