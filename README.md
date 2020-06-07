# Extractive-Text-Summarization
Unsupervised learning model based on exhaustive text summarization

Here we use cosine similarity to find similar sentences, and use networkx to rank the most important sentences in a paragraph, then print the top "n" important sentences of the paragraph as a summary. This method, unlike "Abstractive Summarization", doens't take the meaning of the word(s) in account, or in a way the semantics , but rather just ranks the sentences based on similarity. This method is useful in cases where you want a short summary of the key points in a passage. The benefit is you don't need to train a model for this as this uses simple cosine similarity. 
