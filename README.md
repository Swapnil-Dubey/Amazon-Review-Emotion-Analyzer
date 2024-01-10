# Amazon Review Emotion Analyzer
## Overview:
This project aims to provide an in-depth analysis of emotions expressed in Amazon product reviews. Using the Rainforest API, it fetches reviews of a specified product, conducts sentiment analysis, and visualizes the emotional tones present in the aggregated reviews.

## Features:
- Data Retrieval: Fetches Amazon product reviews using the Rainforest API based on the provided URL.
- Sentiment Analysis: Utilizes the text2emotion library to gauge emotional tones in the collected reviews.
- Visualization: Presents a pie chart visualizing the distribution of emotions found in the reviews.
- User Interface: Utilizes Tkinter for a user-friendly interface to input the Amazon product URL and view the emotional analysis results.
## Technologies Used:
- Python
- Requests library for API interaction
- text2emotion for sentiment analysis
- Matplotlib for data visualization
- Tkinter for the graphical user interface (GUI)
- NLTK for natural language processing tasks
## How to Use:
1. Input the URL of the Amazon product page.
2. Click "Confirm" to trigger the analysis process.
3. View the top positive and negative reviews along with a pie chart depicting emotional analysis.
## Installation:
Ensure the required libraries (requests, text2emotion, nltk) are installed. Use Python 3.x to run the script.

## Usage: 
   python amazon_review_analyzer.py
## Note:
This project requires an internet connection to fetch Amazon product reviews via the Rainforest API.
Emotion analysis accuracy may vary based on the reviews' content and language nuances.
