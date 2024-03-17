# Emoji Sentiment Analysis

## Introduction
Emoji sentiment analysis is a field at the intersection of NLP and emotion AI. By analyzing the sentiment behind emojis used in digital communications, we can gain insights into users' emotions and sentiments, enhancing our understanding of digital communication patterns.

## Problem Description
The widespread use of emojis in digital communication presents an opportunity to analyze sentiments expressed non-verbally (or expressed verbally, but complemented by emojis). However, interpreting the sentiment of emojis accurately poses a challenge due to their varied and context-dependent meanings. This project leverages data from two of the most popular social media platforms, WhatsApp and Instagram, to explore this challenge.

## Objective
The main objective of this project is to develop a machine learning model capable of analyzing the sentiment of emojis within the context of text messages or social media posts. One of the potential applications of this analysis is to track individuals' feelings and provide practitioners with insights to improve patients' mental health by analyzing the emotions conveyed through emojis.

## Methodology
- **Data Collection**: Our data comes from chats exported from WhatsApp and comment to posts exported from Instagram. Any user can export their WhatsApp data directly and request their Instagram data through the app.
- **Data Preprocessing**: We use packages such as csv, nltk, re, pandas, json, emojis, and numpy for processing. The process involves loading an emoji catalog, uploading chat data, connecting it to a catalogue of feelings (each emoji in the catalogue is assessed as expressing _positive_, _negative_ or _neutral_ emotions), tokenizing emojis, and merging data into a final dataset categorized by sentiment.
- **Model Selection and Analysis**: Details about the specific machine learning models used are streamlined for the project's context, focusing on sentiment analysis and categorization. Charts are provided, showcasing the different usage of emojis across WhatsApp and Instagram, separately or altogether.
- **Evaluation**: The evaluation metrics include rankings of emojis (and categories of emojis) and cover rates (how many unique emojis are found across teh WhatsApp/Instagram data as opposed to the total of unique emojis available in the catalogue).

## Results
The analysis outputs include:
- A word cloud drawn from the data, showcasing the most often used emojis.
- Three pie charts showing overall sentiment, as well as sentiment from WhatsApp and Instagram data individually.
- Emoji frequency analysis.
- Cover ratios indicating the percentage of unique emojis found in the catalog compared to those in the data. The WhatsApp cover rate is 85.71%, and Instagram's is 92.45%.

These results have the potential of offering valuable insights into the emotional sentiments expressed through emojis on social media platforms, aiding in the psychological assessment and therapy processes.

## Future Developments
A possible future development of this project could see a different categorization of emojis, with smaller groups of emojis divided in more categories. Instead of expressing positive, negative, or neutral emotions, we could categorize emojis showing happiness, anger, tiredness, impatience etc. Then, by re-running the script, we could have better insights of the patients' emotional status.
