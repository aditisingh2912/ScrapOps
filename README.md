# ScrapOps
This project scrapes articles from company websites and extracts detailed text-based and sentiment features, storing them in a structured CSV format. It's designed for building downstream NLP applications like readability analysis, tone classification, and summarization
# Overview
The objective of this project is to analyze BlackCoffer blog articles by extracting and evaluating a range of linguistic and sentiment-based features. Using metrics such as word count, average words per sentence, average sentence length, percentage of complex words, and Fog Index, we assess the textual complexity and readability of each article. Additionally, sentiment indicators like positive and negative scores, polarity, and subjectivity scores help us understand the emotional tone of the content. Other features, including personal pronoun usage and average word length, offer deeper insights into the writing style and narrative voice. Together, these computed attributes provide a comprehensive, data-driven perspective on the language and sentiment patterns across the blog’s articles
# Key Computed Variables
URL: The link to the original blog article used as the data source.

Cleaned_Article: The preprocessed version of the article text with noise (like HTML tags, punctuation, stopwords) removed.

Transformed_Text: The final form of the article text after tokenization, lemmatization, or other NLP transformations, ready for analysis.

Word_Count: The total number of words in the cleaned article, indicating article length.

Avg_Word_Per_Sentence: Average number of words used per sentence, useful for understanding sentence density.

Avg_Sentence_Length: The average number of characters or words per sentence, reflecting writing complexity.

Percentage_Complex_Words: Proportion of words in the article that are classified as complex (typically 3+ syllables).

Fog_Index: Provides an estimate of the readability of the content based on sentence and word complexity

Personal_Pronouns_Count: Number of personal pronouns (I, we, you, etc.) used, indicating subjectivity or personal tone.

Avg_Word_Length: The average number of characters per word, often correlating with vocabulary complexity.

Complex_Word_Count: Total number of complex words in the article, used in readability analysis.

Positive_Score: A measure of how many positively connotated words appear in the article.

Negative_Score: A measure of how many negatively connotated words appear in the article.

Polarity_Score: A normalized score reflecting the overall sentiment of the article (positive vs. negative).

Subjectivity_Score: A score representing how subjective (opinion-based) or objective (fact-based) the content is.
# Later Improvements
Run extractive summarization (e.g., TextRank) on it.

Combine statistical + extractive summary for richer results.

Use LLMs to summarize based on extracted metadata and/or short snippets.

Build Company News Alert System 

# Acknowledgements
Special thanks to BlackCoffer for providing access to their blog articles, which served as the foundation for this analysis. Appreciation is also extended to the open-source NLP community for their powerful tools and resources that made this project possible


