# Games of Thrones - Data Science Projects

This repository contains data science projects centered around the *Game of Thrones* universe. The projects explore and analyze text data from the show, leveraging machine learning and natural language processing (NLP) techniques. The goal is to gain insights from dialogues, characters, and other textual elements.

## Table of Contents
- [Overview](#overview)
- [Projects](#projects)
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a data-driven exploration of the *Game of Thrones* world, focusing on the unique language used by characters. By applying text processing, sentiment analysis, and word frequency techniques, we uncover the patterns in the characters' dialogue. It is ideal for those who want to explore text mining and NLP in a fun and practical way.

## Projects

### 1. **Unique Character Dialogues**
   - This project extracts and processes unique dialogue for each major character.
   - **Goal**: Understand the distinct speech patterns of different characters.
   - **Core Tasks**: Text parsing, data cleaning, and outputting results to individual files.

### 2. **Sentiment Analysis**
   - Analyzes the sentiment (positive, negative, neutral) of various characters' dialogues.
   - **Tools**: TextBlob, VADER.
   - **Goal**: Understand how the sentiment of the characters' language evolves throughout the series.

### 3. **Word Frequency Analysis**
   - Identifies frequently used words and phrases by the characters.
   - **Goal**: Discover the most important or repeated themes.
   - **Tools**: NLTK, Pandas.

### 4. **Named Entity Recognition (NER)**
   - Detects and categorizes named entities like people, places, and organizations in *Game of Thrones* texts.
   - **Goal**: Build a list of key entities mentioned in the dialogues.
   - **Tools**: SpaCy.

## Installation

To use this repository, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/jarvismayur/Games-of-Thornes---Data-Scince-Projects.git

   Navigate to the project directory:

  ```bash
  cd Games-of-Thornes---Data-Scince-Projects

2. Set up a Python virtual environment and install the required libraries:

    ```bash
    Copy code
    # Create virtual environment
    python -m venv venv

    # Activate the virtual environment
    # On Windows:
    venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate
    
    # Install dependencies
    pip install -r requirements.txt
Technologies Used
Python: Main programming language used.
Pandas: Data manipulation.
NLTK: Natural Language Processing.
SpaCy: Named Entity Recognition (NER).
TextBlob: Sentiment analysis.
Matplotlib & Seaborn: Data visualization.
Jupyter Notebook: For project development.
Usage
You can run any of the projects in this repository by navigating to the project folder and executing the corresponding Jupyter notebook or Python script. For example, to analyze character dialogues:

bash
Copy code
cd Unique-Character-Dialogues/
jupyter notebook dialogue_analysis.ipynb
Contributing
If you'd like to contribute to this repository:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a pull request.
License
This project is licensed under the Apache License 2.0. See the LICENSE file for more information.

vbnet
Copy code

This `README.md` provides an overview of your repository, instructions for installation and usage, and highlights the projects included. Let me know if you'd like any adjustments!





