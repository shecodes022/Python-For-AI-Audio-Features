# About this Repository 📌

This repository contains the mini project I did as a part of the coursework for the module [Python Programming for Artificial Intelligence](https://qmplus.qmul.ac.uk/course/view.php?id=29228). The assignment used the MLEnd Spoken Numerals Dataset to extract features from audio recordings of a single speaker, analyse them, and build a function that finds similar-sounding audio files.


# Key Takeaways 🔍

1. Data Exploration: Loaded and summarised the audio attribute and speaker demographic files (speakers, numerals and intonations) for over 32,000 recordings.

2. Audio Processing: Read and cleaned `.wav` files, then separated the silent and non-silent parts of each recording.

3. Feature Extraction: Wrote functions to compute 10 audio features per file, including duration, energy, zero-crossing rate and the mean and standard deviation of positive and negative samples.

4. Comparative Analysis: Compared features across numerals and intonations (bored, excited, neutral, question) using statistics and visualisations.

5. Similarity Search: Built a function that takes an audio filename and returns the 10 most similar audio files based on the extracted features.


# Stack 🛠️

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


# Environment 👩🏻‍💻
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)


# Libraries ⚙️

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)


# Repository Structure 🌲
```text
├──.gitattributes
├── Assignment_2.ipynb
├── README.md
└── Speaker_3_Audio_features.csv
```

# Reflection 🪞
This project showed how raw audio can be turned into meaningful numerical features that describe how something is said, not just what is said. Separating silence from speech and computing features such as energy and zero-crossing rate gave me practical experience with signal processing in Python.

Comparing numerals and intonations highlighted how much open-ended analysis depends on choosing the right features and explaining the results clearly. Building the similarity function also gave me an introduction to the ideas behind speaker identification and audio retrieval systems.
