Book Recommendation Chatbot

Overview

This project is an AI-powered chatbot that recommends books based on user preferences. It utilizes Natural Language Processing (NLP) with NLTK for text preprocessing and a weighted recommendation system driven by simulated user feedback. Interactive visualizations aid in exploratory data analysis and system evaluation.

Features
Text Processing: Tokenizes, removes stopwords, and lemmatizes user input.

Personalized Recommendations: Uses weighted genres for personalized book suggestions.

Data Visualization: Displays user feedback, interaction patterns, and refined genre weights.

Interactive Search: Includes a mini search bar for genre selection and detailed recommendations.

Prerequisites
Python 3.8+

Required libraries: nltk, matplotlib

NLTK datasets: punkt, stopwords, wordnet

Installation
Clone the repository:

text
git clone <repo_url>
cd <repo_name>
Install dependencies:

text
pip install nltk matplotlib
Download necessary NLTK data:

python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
Usage
Run the Script: Execute the main script to view visualizations, test the recommendation system, and interact with the mini search bar:

text
python main.py
Interactive Search: The mini search bar displays available genres; select a genre to see book recommendations.

Project Structure
Part 1: Library imports and NLTK dataset downloads.

Part 2: Data preprocessing functions.

Part 3: EDA modules with plotting functions for feedback and recommendations.

Part 4: Recommendation system based on weighted genres.

Part 5: Mini search bar for interactive genre-based recommendations.

Part 6: Testing and output display.

Future Improvements
Integrate a larger and real-world book dataset.

Enhance NLP to better handle ambiguous inputs.

Improve interactivity with a web-based or mobile interface.
