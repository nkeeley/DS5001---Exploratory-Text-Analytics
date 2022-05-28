# DS5001 - Exploratory Text Analytics

Language types: Python

This repository contains assignments and projects associated with exploratory text analytics. Topics include manual text cleansing/OHCO chunking using regex, parts of speech annotation, term-frequency analysis, n-gram analysis, agglomerative clustering, principal components analysis, topic modeling, and semantic algebra through word embeddings. For sentiment analysis-related content covered in class, please see https://github.com/nkeeley/Exploring-Company-Earnings-Calls. Note: All assignments were based off of templates provided by the professor, and adapted to meet the needs of assigned problem solutions and different corpora.

### Keeley_Manual-M3 Assignment_4FEB2022 

In this assignment, I manually uploaded and cleaned a gutenberg project (https://www.gutenberg.org/) text, including cruft removal, chapter identification (through regex), OHCO chunking, and tokenization. I then generated a "VOCAB" table and an n-gram model, followed by n-gram analysis/redundancy calculations on the text. 

### Keeley_M4 Assignment_13FEB2022(1) 

In this assignment, I created a "library" table (LIB) of several texts within a gutenberg project corpus. Using a wrapper function containing NLTK functions, I annotated stems, stopwords, and parts-of-speech. Finally, I queried the resulting tables for insights.

### Keeley_M05_01_BOW_TFIDF-Copy1 

In this assignment, I created bag-of-word (BOW) and term-frequency inverse document frequency generation functions and ran them on a corpus of texts. I then queried the vocabulary and BOW tables for term significance.

### M06_01_SimilarityMeasures-Copy1(1) 

In this assignment, I used the BOW/TFIDF generation functions from Assignment 5, filtered the top 1000 most significant terms per book in the corpus, normalized the term-document vectors for length, generated a "pair" table of each word paired to each other word, and conducted hierarchical clustering to visualize similarities between different books in the corpus.

### Keeley_V2_M07_01_PCA-REVISED-Copy1(1).ipynb

In this assignment, I utilized a Principal Components Analysis function covered in class to generate loadings for a corpus. I visualized the principal components for documents within the corpus using plotlyexpress interactive visualization functions.

### Keeley_M8 Assignment_30MAR2022(1).ipynb

In this assignment, I utilized a wrapper function for Sklearn's LDA function covered in class to generate topics for a corpus of dating profiles. The topic content of these profiles was then analyzed by grouping profiles along demographic/socio-economic lines.

### M09_04_word2vec-Copy1.ipynb

I was unable to find my notebook submission for this assignment. However, this is the template provided in class, which I adapted for the problems proposed. This notebook contains instructions for producing word embeddings via the word2vec function, visualizing t-distributed stochastic neighbor embeddings (T-SNE), and conducting semantic algebra on the embeddings.
