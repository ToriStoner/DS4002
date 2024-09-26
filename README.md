# README

## Contents of the Repository
This repository contains a project focused on analyzing Yelp customer reviews for Los Angeles restaurants, with the goal of identifying correlations between review sentiment and star ratings. Using VADER for sentiment analysis and Naive Bayes classification, the project aims to predict the sentiment of customer reviews and evaluate if positive reviews correlate with higher restaurant ratings. The project also includes statistical testing to determine the significance of these correlations. Everything has been written and completed by Tori Stoner, Aniyah McWilliams, and Adam Chow.

### Section 1: Software and Platform
- **Software**: Google CoPython 3.x
- **Add-on Packages**: 
  - `pandas` 
  - `numpy` 
  - `matplotlib` 
  - `seaborn` 
  - `scikit-learn`
  - `nltk` (for VADER sentiment analysis)
  - `wordcloud` (for word cloud generation)
  - `GaussianNB` (for Naive Bayes)
  - `gensim` (for LDA Analysis)
- **Platform**: Tested on Google Colab (Linux-based environment)

### Section 2: Map of the Documentation
```
Project_Folder/
│
├── data/
│   └── top240.csv           # Dataset of Yelp reviews for LA restaurants
│
├── notebooks/
│   └── sentiment_analysis.ipynb  # Jupyter notebook for data processing, VADER sentiment analysis, and model implementation
│
├── images/
│   └── wordcloud.png        # Word cloud visualization
│
├── results/
│   └── correlation_output.txt   # Text output of the r-squared and p-value results
│
└── README.md                # This file
```

### Section 3: Instructions for Reproducing the Results
1. **Set up environment**:
   - Install Python 3.12.6.
   - Install necessary packages using pip:
     ```
     pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud
     ```
   
2. **Download dataset**:
   - Place the `top240.csv` file in the `data/` folder.

3. **Run sentiment analysis**:
   - Open `sentiment_analysis.ipynb` in Google Colab or Jupyter.
   - Run all cells to preprocess the data, compute VADER sentiment scores, and build the Naive Bayes model.

4. **Generate results**:
   - View statistical outputs in the notebook and the correlation result in `results/correlation_output.txt`.

5. **Visualize word cloud**:
   - Generated word cloud can be found in `images/wordcloud.png`.
