
# January 6th Capitol Attack Text Analysis

## Project Overview

This repository is dedicated to text analysis tasks that delve into the coverage of the January 6th attack on the United States Capitol. It encompasses a comprehensive corpus, `cnn_fox_corpus.rdata`, which contains transcripts along with their metadata from news segments aired on CNN and Fox News from January 7, 2021, to January 7, 2022. These segments specifically include mentions of "January 6" and "Capitol." The analyses conducted here leverage techniques such as tokenization, document feature matrices, co-occurrences, Zipf's law examination, and cosine similarity measures to draw parallels between the content on Wikipedia and the narratives presented in the news transcripts.

## Visualizations
Our analyses have yielded a variety of insights, encapsulated notably in the word cloud derived from the Document Feature Matrix (DFM) with TF-IDF weighting. This visual representation underscores the prevalence of specific terms within the corpus of news scripts, highlighting the most frequently discussed names and topics within the context of the January 6th event.
### Word Could
![results:wordcloud](https://github.com/yoiestelle/CNN-FOX-News-Analysis/assets/144069476/96b0efe4-5813-40ea-9c57-7cc4332ed298)


### Feature Co-occurrence Analysis
In our study, we explored the relationships between key terms in the news coverage from CNN and Fox News. The feature co-occurrence matrices (FCM) were generated from a document-feature matrix (DFM) with TF-IDF weighting to visualize how often pairs of terms occurred together in the same documents.

#### CNN Co-occurrence Network
The network plot for CNN highlights the interconnectivity between terms within their news segments, revealing the central topics and how they are associated with one another.
![image](https://github.com/yoiestelle/CNN-FOX-News-Analysis/assets/144069476/90bfc02a-761d-4941-ae66-6fc817f29e3b)

#### Fox News Co-occurrence Network
Similarly, the network plot for Fox News illustrates the most prominent terms in their coverage and the connections between them, providing insights into the thematic structure of their reporting.
![image](https://github.com/yoiestelle/CNN-FOX-News-Analysis/assets/144069476/2452e845-a014-47d2-b8da-e49b9f255723)
