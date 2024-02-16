# Sentiment Analysis of two Ted Speaker in R

## Introduction
This report analyzes TED talks by Hans Rosling and Deborah Gordon, experts in data analysis and biology, respectively. Hans Rosling's talks focus on global issues like health and poverty, while Deborah Gordon explores the intricate world of ant colonies. The report aims to uncover main themes, frequently used words, and differences in language usage and sentiment between the speakers, identifying patterns and recurring themes in their talks.

## Method
This report employs Tidying and Tokenization techniques, utilizing unnest_tokens(), anti_join(), and get_stopwords() to structure and filter words in the TED talks of Hans Rosling and Deborah Gordon. Word Frequency Analysis is then applied, grouping and filtering the data to identify the most frequent words. Odds-Ratios, computed through dsEssex functions like compute_OR() and log_OR(), are used to compare the emotional tones of the two speakers. Additionally, Sentiment Analysis using NRC Sentiment and Emotion lexicons reveals patterns and prevalent emotions in their speeches. The objective is to gain insights into the common words, emotions, and speech patterns of Hans Rosling and Deborah Gordon, providing a holistic understanding of their communication styles.

## Results
The analysis of TED talks by Hans Rosling and Deborah Gordon highlights their distinct language patterns and focuses. Hans Rosling's speeches center on global issues, emphasizing words like 'can', 'world', and 'countries', conveying positive emotions. In contrast, Deborah Gordon's talks delve into ant colonies, with a neutral emotional tone. Various techniques, including sentiment analysis and Odds-Ratios, contribute to these observations, providing a comprehensive understanding of their communication styles and themes.
