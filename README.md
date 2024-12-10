# Concall Sentiment Analysis

This project focuses on extracting and analyzing sentiments from **conference call (concall) transcripts** using **Natural Language Processing (NLP)**. It identifies positive, negative, and neutral sentiments, offering deeper insights into the tone of discussions. The project calculates sentiment scores using **VADER** and **Afinn**, helping investors and analysts assess company performance and make informed decisions.  

## Key Features  
- **Sentiment Analysis**: Utilizes VADER for compound sentiment scores and Afinn for text-based sentiment scoring.  
- **PDF and Excel Data Support**: Analyzes data from both PDFs and Excel files.  
- **Word Tokenization**: Uses **NLTK** to preprocess and tokenize the text content.  
- **Positive and Negative Word Extraction**: Highlights key words contributing to the overall sentiment.  
- **Score Normalization**: Adjusts sentiment scores based on document length to ensure fair comparisons.  
- **CSV Export**: Saves the detailed analysis in a CSV file for further exploration.


## Libraries Used
- **VADER Sentiment**: For fine-grained sentiment analysis
- **Afinn**: For scoring text sentiment
- **NLTK**: For text processing and tokenization
- **PyPDF2**: For PDF extraction
- **Pandas**: For data manipulation

## How It Works  
The process starts with uploading concall data (in **PDF or Excel** format). The text is tokenized and analyzed using **VADER** to generate sentiment scores for each section, while **Afinn** computes an overall sentiment score. Words contributing to positive or negative sentiment are extracted, and the scores are normalized to account for variations in document size. The final results, including sentiment metrics and word counts, are exported as a **CSV file** for further analysis.

## Results  
This analysis provides sentiment scores, positive and negative word counts, and normalized sentiment metrics. It enables stakeholders to better understand the tone behind the discussions, helping assess the company’s performance over time.

## Conclusion  
This project demonstrates how **NLP-based sentiment analysis** can extract meaningful insights from concall transcripts. It equips analysts and investors with valuable tools to evaluate the tone and sentiment of conversations, enhancing decision-making and performance tracking.
