# ScrapOps
This project scrapes articles from company websites and extracts detailed text-based and sentiment features, storing them in a structured XSLX format. It's designed for building downstream NLP applications like readability analysis, tone classification, and summarization
# Overview
The objective of this project is to analyze BlackCoffer blog articles by extracting and evaluating a range of linguistic and sentiment-based features. Using metrics such as word count, average words per sentence, average sentence length, percentage of complex words, and Fog Index, we assess the textual complexity and readability of each article. Additionally, sentiment indicators like positive and negative scores, polarity, and subjectivity scores help us understand the emotional tone of the content. Other features, including personal pronoun usage and average word length, offer deeper insights into the writing style and narrative voice. Together, these computed attributes provide a comprehensive, data-driven perspective on the language and sentiment patterns across the blog’s articles
# Key Computed Variables
1. URL: The link to the original blog article used as the data source.

2. Cleaned_Article: The preprocessed version of the article text with noise (like HTML tags, punctuation, stopwords) removed.

3. Transformed_Text: The final form of the article text after tokenization, lemmatization, or other NLP transformations, ready for analysis.

4. Word_Count: The total number of words in the cleaned article, indicating article length.

5. Avg_Word_Per_Sentence: Average number of words used per sentence, useful for understanding sentence density.

6. Avg_Sentence_Length: The average number of characters or words per sentence, reflecting writing complexity.

7. Percentage_Complex_Words: Proportion of words in the article that are classified as complex (typically 3+ syllables).

8. Fog_Index: Provides an estimate of the readability of the content based on sentence and word complexity

9. Personal_Pronouns_Count: Number of personal pronouns (I, we, you, etc.) used, indicating subjectivity or personal tone.

10. Avg_Word_Length: The average number of characters per word, often correlating with vocabulary complexity.

11. Complex_Word_Count: Total number of complex words in the article, used in readability analysis.

12. Positive_Score: A measure of how many positively connotated words appear in the article.

13. Negative_Score: A measure of how many negatively connotated words appear in the article.

14. Polarity_Score: A normalized score reflecting the overall sentiment of the article (positive vs. negative).

15. Subjectivity_Score: A score representing how subjective (opinion-based) or objective (fact-based) the content is.

# Later Improvements
1. Use LLMs to finetune the cleaned Articles for News Summariser.

2. Deployment

# Contributing
Please follow these steps:

1. Fork the repository  
2. Create a new branch for your feature  
3. Commit your changes with clear messages  
4. Push to your fork  
5. Submit a pull request  


# License
MIT License - see LICENSE file for details

# Acknowledgements
Special thanks to BlackCoffer for providing access to their blog articles, which served as the foundation for this analysis. Appreciation is also extended to the open-source NLP community for their powerful tools and resources that made this project possible


