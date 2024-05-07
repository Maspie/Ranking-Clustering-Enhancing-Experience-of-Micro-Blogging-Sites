# Enhancing Content Discovery on Microblogging Sites

## Project Overview
This project develops a comprehensive framework to enhance the discovery and accessibility of content on microblogging platforms such as Twitter. Utilizing advanced Natural Language Processing (NLP) and Machine Learning (ML) techniques, the project aims to address the common challenge of navigating through vast, unstructured data to find relevant and engaging content. By clustering, ranking, and summarizing tweets, this system not only helps users explore topics of interest more efficiently but also enhances overall user engagement by presenting content in a more structured and digestible manner.

## Objectives
- **Improve Content Navigation**: Help users navigate through large volumes of tweets by clustering similar content together, making it easier to find relevant discussions.
- **Enhance User Engagement**: Increase user engagement by ranking tweets based on relevance, ensuring that the most pertinent tweets are highlighted.
- **Summarize Information**: Provide users with quick summaries of topics, saving time and enhancing the comprehension of complex discussions.

## Features
- **Tweet Clustering**: Uses iterative K-means clustering to group tweets based on their semantic content. This method identifies natural groupings of tweets that discuss similar topics, allowing users to explore specific interests.
- **Tweet Ranking**: Implements cosine similarity measures to rank tweets within each cluster according to their relevance to the core topic, prioritizing content that is most likely to be of interest.
- **Automated Summarization**: Employs Retrieval Augmented Generation (RAG) techniques, integrating OpenAI's GPT models to generate concise summaries for clusters. These summaries provide quick insights and help users decide which threads to explore in detail.

## Technologies Used
- **Python**: The primary programming language used for developing the project.
- **Scikit-Learn**: Utilized for implementing machine learning algorithms for clustering.
- **NLTK**: Used for natural language processing tasks such as tokenization and stopwords removal.
- **OpenAI API**: Integrates advanced AI models for generating text summaries.
- **Pandas & NumPy**: Handle data manipulation and mathematical operations.

- ![Image Alt text](Tweets_Preprocessing/Diag.png)  

## Possible Future Works
- Using different clustering techniques.
- Improving RAG and whole model

