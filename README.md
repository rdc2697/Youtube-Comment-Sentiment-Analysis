# YouTube Comment Sentiment Analysis

This project analyzes the sentiment of comments from a YouTube video using BERT for sentiment analysis.

## Project Overview

- **Objective:** To analyze the sentiment of comments on a specific YouTube video.
- **Tools Used:** Python, pandas, transformers, matplotlib, seaborn, Google YouTube Data API.
- **Model:** BERT (distilbert-base-uncased-finetuned-sst-2-english).

## Results

### Sentiment Distribution
### Positive Word Cloud
![wordcloud_positive](https://github.com/rdc2697/Youtube-Comment-Sentiment-Analysis/assets/40556517/071d24e0-6434-4b77-84d6-89a6abed2e88)

### Negative Word Cloud
![wordcloud_negative](https://github.com/rdc2697/Youtube-Comment-Sentiment-Analysis/assets/40556517/b7c29fb3-7649-417d-9e1d-57f335cdde6d)

### Most Positive Comments

| Comment | Sentiment Score |
|---------|-----------------|
| Watched it when it was at 10k views....75 million views layer, its still accurate | 1 |
| Brooooooo | 1 |
| I don't understand why it's in my recommendation.. but it doesn't disappoint. 😅 | 1 |
| it’s exactly 71,696,539! 😃 | 1 |
| Exactly right when I looked at it 4/14/24 at 8:44 AM | 1 |

### Most Negative Comments

| Comment | Sentiment Score |
|---------|-----------------|
| off by ~30 | -1 |
| 71 something something 1 but when i clicked on it it said 71 something something 2 | -1 |
| ''the code was never the import part'' | -1 |
| its wrong it has 16 more views | -1 |
| i finally did it the title says 71,891,637 but it is showing \r\n71,891,642 | -1 |

### Visualizations

#### Sentiment Counts
![sentiment_counts](https://github.com/rdc2697/Youtube-Comment-Sentiment-Analysis/assets/40556517/e1d58329-9b15-4915-a366-167d538ddf5d)

#### Top N Positive Words
![top_positive_words](https://github.com/rdc2697/Youtube-Comment-Sentiment-Analysis/assets/40556517/b6c3f7ea-145e-463c-a087-d14bcfeba815)


#### Top N Negative Words
![top_negative_words](https://github.com/rdc2697/Youtube-Comment-Sentiment-Analysis/assets/40556517/677ca406-7cff-4c27-bab7-2319b760404e)


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/YouTube-Comment-Sentiment-Analysis.git
   cd YouTube-Comment-Sentiment-Analysis
