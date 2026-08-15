# NLP Topic Modelling Analysis
## Project Description
This project analysis consumer complaints of a bank using Natural Language Processing (NLP)
Topic Modelling is used to dig out the themes in the complaint data sets.
Topic Modelling: Finding the topics from a text without reading. In our sample model there are approximately 162K customer complaints and by using topic modelling it was detected which ones are about mortgage, or identity theft etc. Topic modelling finds it automatically. We commanded 5 topics and the model grouped it by checking the words.
## Methods
Text preprocessing: from raw text to “clean text” 
• Normalize by converting text to lowercase and fixing encoding 
• Strip noise by removing special characters, URLs, punctuation, emojis, numbers 
• Tokenize by splitting sentences into individual words 
• Remove stop words such as “the”, “and”, “is” 
• Lemmatize and Stem by reducing words to their root form (e.g., eating → eat or troubled → 
trouble) 
• Filter by removing very rare or very common terms and adding bi-grams
Vectorization: turning text into numbers 
• BoW (Bag of Words), which simply counts how often each word appears in the text 
• TF-IDF, which is an extension of BoW and provides numerical statistics that reflect the importance of a specific word. 
Topic analysis: vectors into topics 
LDA (probabilistic modeling: Each document is a mixture of topics), and NMF (matrix factorization: It factorizes TF-IDF into non-negative parts). (5 topics each)
## Libraries
pandas, numpy, nltk, scikit-learn
## Dataset
Consumer Financial Protection Bureau (CFPB) consumer complaints dataset  
Source: [Kaggle](https://www.kaggle.com/datasets/cfpb/us-consumer-finance-complaints)
