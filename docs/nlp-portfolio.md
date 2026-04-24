# Natural Language Processing Portfolio

Karli Dean

2026-04

This page summarizes my work on **natural language processing** projects.

## 1. NLP Techniques Implemented
In this course, we used multiple techniques for natural language processing. The highlights of which are tokenization, which was used in each project, and text normalization that allows for us to see all words for what they are without formatting.I also learned more on data pipelines and validation of text and transforming our results with a simple code snippet. I also used techniques that taught me how to scrape the web for what I needed and how to pull the text into a usable format with help from BeautifulSoup and other programs. I also learned how to create importance of the words I tokenized by creating graphs and word clouds to visualize frequency and connectivity.


## 2. Systems and Data Sources
[Notable Repository: Week 5 - Web Documents](https://github.com/karlidean/nlp-05-web-documents)\
[Notable Repository: Week 6 - NLP Pipelines](https://github.com/karlidean/nlp-06-nlp-pipeline)\
I worked with HTML web pages, JSON APIs, and plain text, and they all behave differently. HTML is semi-structured, so I had to dig through tags to find what I need, while JSON is much cleaner with defined key-value pairs (but can get tricky with nested data). Plain text is the most difficult to work with since there’s no structure at all, so it requires the most cleaning and normalizing before I could actually analyze anything.\
\
I handled messy data by standardizing and cleaning the text through lowercasing, punctuation removal, whitespace normalization, and stopword filtering with spaCy. I also handled missing or inconsistent values by assigning defaults like “unknown” to keep the dataset complete. This process reduced noise and made the data consistent enough for meaningful NLP analysis.

## 3. Pipeline Structure (EVTL)
[Notable Repository: Week 6 - NLP Pipelines](https://github.com/karlidean/nlp-06-nlp-pipeline)\
I followed an EVTL pipeline to process the data. In the Extract stage, I collected data from sources such as web pages, APIs, and plain text documents. During Validate, I inspected the structure and content to ensure fields were present and handled missing or inconsistent values. In Transform, I applied NLP techniques including text cleaning, normalization, tokenization, and feature engineering to create meaningful signals. Finally, in Load, I output the processed data into a structured dataset for analysis and interpretation.

## 4. Signals and Analysis Methods
[Notable Repository: Week 6 - NLP Pipelines](https://github.com/karlidean/nlp-06-nlp-pipeline)\
I computed NLP features to understand both the content and complexity of the text. This included word frequency through tokenization, basic context through token sequences, and keyword extraction using high-frequency and unique terms. I also engineered special signals like token count, vocabulary richness, and average word length to measure readability and technical complexity. Instead of sentiment analysis, I focused on structural signals that better reflect the nature of research writing.

## 5. Insights
[Notable Repository: Week 6 - NLP Pipelines](https://github.com/karlidean/nlp-06-nlp-pipeline)\
The analysis showed that the abstract is consistently dense and technical, with high vocabulary richness and longer word lengths indicating a specialized audience. One notable finding was how the complexity persisted even after cleaning, highlighting the depth of the content. These results are useful because they turn subjective ideas about difficulty into measurable signals that can be compared across documents.


## 6. Representative Work
[Repository from Week 3: Text Exploration](https://github.com/karlidean/nlp-02-text-preprocessing)\
This repo shows that I can take cleaned text and actually analyze it, identifying patterns like word frequency, category differences, and co-occurrence. It highlights my ability to interpret how meaning shows up in language, not just prepare the data.\
\
[Repository from Week 5: Web Documents](https://github.com/karlidean/nlp-05-web-documents)\
This repo shows that I can take a structured NLP pipeline and actually make it my own by modifying the validation and transform stages for real web data. It highlights my ability to inspect messy HTML, handle inconsistencies, and turn it into clean, meaningful features for analysis.\
\
[Repository from Week 6: NLP Pipelines](https://github.com/karlidean/nlp-06-nlp-pipeline)\
This repo shows that I can take an existing NLP pipeline and actually understand and adapt it, not just run it. By modifying the src/nlp modules, I was able to process real text data, engineer useful features, and produce clean, structured outputs.


## 7. Skills
This work highlights my skills in Python data processing, where I used libraries like pandas, BeautifulSoup, and spaCy to manipulate and analyze text data. I demonstrated the ability to work with unstructured and semi-structured text by cleaning, normalizing, and extracting meaningful features. I also handled messy or inconsistent inputs by validating structure, managing missing values, and standardizing formats to ensure reliable outputs.\
\
Additionally, I built and adapted repeatable NLP pipelines, showing that I can structure workflows that are scalable and reproducible. Finally, I communicated results professionally through clear documentation, Markdown explanations, and structured outputs that make the analysis easy to interpret.
