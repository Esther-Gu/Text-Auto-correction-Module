# Text Auto-correction Module

## Introduction

The Text Analytics and Autocorrection Module is a Python-based program aimed at measuring typing speed and implementing a typing autocorrect feature. The module performs text classification tasks, keyword matching, and provides real-time analytics for typing speed and accuracy.

[Watch my implementation on YouTube](https://youtu.be/ENGe_OFuRbk)

![Text Analytics and Autocorrection Interface](images/Cats_proj.png)

## Features

### Text Classification
- Achieves up to 90% accuracy in classifying text into various categories.
- Utilizes basic natural language processing techniques.

### Autocorrection
- Implements dynamic programming and edit distance algorithms.
- Optimized for fast execution using memoization techniques.

### Typing Metrics
- Real-time calculation of Words Per Minute (WPM) and accuracy.
- Multiplayer progress tracking and competitive typing metrics.

## Technologies Used
- Python
- Dynamic Programming
- Edit Distance Algorithms
- Memoization

## Implementation Details

### Text Classification & Keyword Matching
- Utilizes `choose` and `about` functions to select paragraphs that match a set of keywords. 

### Typing Speed and Accuracy Analytics
- Features an `accuracy` function that calculates the percentage of words typed correctly when compared to a reference string.
- Includes a `wpm` function for calculating words-per-minute based on the typed string and elapsed time.

### Autocorrection Mechanism
- Employs an `autocorrect` function that finds the most similar word from a set of valid words based on a provided difference function and a limit.

### Utilitarian Functions
- Leverages utility functions from an external `utils` module for string manipulations such as converting to lowercase and removing punctuation.

### Additional Highlights
- **Flexibility**: The architecture is designed to allow easy integration of additional features or different difference functions.
- **Efficiency**: Makes efficient use of Python's list comprehensions and `min()` function for optimized operations.

## Acknowledgements

This project was created as part of online coursework at [UC Berkeley](https://inst.eecs.berkeley.edu/~cs61a/su20/proj/cats/). Special thanks to UC Berkeley for providing the opportunity and inspiration for this project.

