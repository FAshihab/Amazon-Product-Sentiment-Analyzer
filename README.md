# Amazon Product Sentiment Analyzer

## Project Description
[cite_start]This project was developed to streamline the analysis of customer opinions on online shopping platforms like Amazon[cite: 33, 34]. [cite_start]The system utilizes **Natural Language Processing (NLP)** to automatically identify and classify emotions expressed in written reviews, focusing specifically on the "unlocked mobile phones" category[cite: 38, 41, 42]. [cite_start]By converting large amounts of textual data into meaningful insights, the solution helps sellers summarize customer satisfaction and highlight common product concerns[cite: 36, 43].

---

## How It Works
[cite_start]The application processes data through a structured pipeline to ensure accurate sentiment categorization[cite: 68]:

* [cite_start]**Function Implementation:** A core `sentimentAnalyzer(text)` function was built using the **TextBlob** library to compute polarity scores for every review[cite: 69, 71].
* [cite_start]**Data Enrichment:** The system adds new "Sentiment" and "Polarity" columns to the dataset, allowing for automated grouping and classification[cite: 72, 73, 74].
* [cite_start]**Sample Extraction:** The model uses `groupby` operations to extract representative examples from each sentiment category (Positive, Neutral, Negative) for accuracy evaluation[cite: 75, 76, 77, 78].
* [cite_start]**Stopwords Filtering:** To isolate the root causes of negative feedback, the system removes common English stopwords (e.g., "the," "with") to focus on meaningful keywords[cite: 79, 80, 81].
* [cite_start]**Visualization:** Insights are presented through bar charts that illustrate the overall distribution of customer sentiments across the dataset[cite: 452, 906].

---

## Technical Stack
* [cite_start]**Language:** Python [cite: 39]
* [cite_start]**Core AI Library:** **TextBlob** (used for lightweight and effective sentiment classification) [cite: 39, 40]
* [cite_start]**Data Analysis:** **Pandas** (used for DataFrame management and CSV processing) [cite: 90, 139]
* [cite_start]**Visualization:** **Matplotlib** (used for generating bar charts and distribution figures) [cite: 444, 451]
* [cite_start]**NLP Utilities:** **NLTK** (Natural Language Toolkit) specifically for advanced stopword removal and text cleaning [cite: 600, 601]
