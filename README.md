**Amazon Product Sentiment Analyzer**

**Project Description**

This project was developed to streamline the analysis of customer opinions on online shopping platforms like Amazon. The system utilizes Natural Language Processing (NLP) to automatically identify and classify emotions expressed in written reviews, focusing specifically on the "unlocked mobile phones" category. By converting large amounts of textual data into meaningful insights, the solution helps sellers summarize customer satisfaction and highlight common product concerns.

**How It Works**

The application processes data through a structured pipeline to ensure accurate sentiment categorization:Function Implementation: A core sentimentAnalyzer(text) function was built using the TextBlob library to compute polarity scores for every review.Data Enrichment: The system adds new "Sentiment" and "Polarity" columns to the dataset, allowing for automated grouping and classification.Sample Extraction: The model uses groupby operations to extract representative examples from each sentiment category (Positive, Neutral, Negative) for accuracy evaluation.Stopwords Filtering: To isolate the root causes of negative feedback, the system removes common English stopwords (e.g., "the," "with") to focus on meaningful keywords.Visualization: Insights are presented through bar charts that illustrate the overall distribution of customer sentiments across the dataset.

**Technical Stack**

Language: Python 
Core AI Library: TextBlob (used for lightweight and effective sentiment classification) 
Data Analysis: Pandas (used for DataFrame management and CSV processing) 
Visualization: Matplotlib (used for generating bar charts and distribution figures) 
NLP Utilities: NLTK (Natural Language Toolkit) specifically for advanced stopword removal and text cleaning
