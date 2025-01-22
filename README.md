
# 🧑🏻‍⚕️ Doctor-Patient Conversation Analysis Project

This project demonstrates a comprehensive pipeline for analyzing conversations using Natural Language Processing (NLP) techniques. The analysis includes sentiment detection, emotion classification, named entity recognition (NER), readability scoring, lexical diversity computation, and visualization using word clouds.

---

## ⭐ Table of Contents

1. [📖 Project Overview](#-project-overview)
2. [✨ Features](#-features)
3. [🛠️ Setup Instructions](#️-setup-instructions)
4. [📊 Example Outputs](#-example-outputs)
5. [🖥️ Interactive Gradio Interface](#️-interactive-gradio-interface)
6. [📊 Dashboard](#-dashboard)
7. [🎨 Visualizations](#-visualizations)

---

## 📖 Project Overview

This project processes conversation data to extract meaningful insights. It uses Python libraries such as `spaCy`, `TextBlob`, `Gradio`, and `Transformers` to:

- Analyze sentiment and emotions in text.
- Perform named entity recognition (NER).
- Compute metrics like subjectivity, polarity, lexical diversity, and readability.
- Generate word cloud visualizations for better comprehension of text.
- Provide an interactive Gradio interface for user interaction.

---

## ✨ Features

- **Sentiment Analysis**: Determines whether the sentiment is positive, negative, or neutral.
- **Emotion Detection**: Detects specific emotions such as joy, anger, sadness, etc.
- **Named Entity Recognition (NER)**: Identifies and classifies entities like names, dates, and locations in text.
- **Lexical Diversity**: Measures the variety of vocabulary used.
- **Readability Scoring**: Computes the Flesch-Kincaid grade level for input text.
- **Word Cloud Generation**: Visualizes the most frequently occurring words.
- **Interactive Gradio Interface**: Allows users to input text and view analysis results interactively.

---

## 🛠️ Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/svnmurali-2004/Docors-Patient-Conversations-Analysis
   cd Docors-Patient-Conversations-Analysis
   ```

2. **Install Dependencies**:
   Ensure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

   Example dependencies:
   ```
   spacy
   pandas
   textstat
   textblob
   wordcloud
   matplotlib
   transformers
   gradio
   ```

3. **Download NLP Models**:
   Download the necessary models for `spaCy`:
   ```bash
   python -m spacy download en_core_web_sm
   ```

4. **Verify Installation**:
   Run a small test script to ensure everything is installed correctly.

---
## 📊 Example Outputs

### Sentiment Analysis and Emotion Detection
![Sentiment Example](img/ex1.png)

### Named Entity Recognition
![NER Example](img/ex1.1.png)

### Readability and Lexical Diversity Metrics
![Readability Example](img/ex1.2.png)

### Word Cloud Visualization
![Word Cloud Example](img/ex1.3.png)

---

## 🖥️ Interactive Gradio Interface

An interactive interface is provided using Gradio to allow users to analyze conversations effortlessly. The interface includes:

- Text input for conversation data.
- Outputs for:
  - Sentiment label and score.
  - Attention level.
  - Tone.
  - Named entities.
  - Emotion analysis in JSON format.
  - Subjectivity and polarity scores.
  - Lexical diversity.
  - Readability score.
  - Word cloud visualization.

---

## 📊 Dashboard

![Dashboard](img/dashboard.png)



## 🎨 Visualizations

### Word Cloud
![Word Cloud](img/wordcloud.png)
---
