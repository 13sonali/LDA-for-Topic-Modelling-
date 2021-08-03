
## Topic Modelling
Topic modelling is a technique for automatically detecting subjects in a text item and deducing hidden patterns from a corpus of text. As a result, improved decision-making is aided. Topic modelling is not the same as rule-based text mining techniques. It's an unsupervised method for locating and observing groups of words in big groups of texts. Topics are defined as "a pattern of co-occurring terms in a corpus that repeats itself." A decent subject model should yield words like "health," "doctor," "patient," and "hospital" for the topic of healthcare, and "farm," "crops," and "wheat" for the topic of farming.

## Latent Dirichlet Allocation (LDA) for Topic Modeling
 Latent Dirichlet Allocation is the most popular topic modeling technique. LDA thinks that papers are made up of a variety of subjects. The probability distribution of those subjects is then used to construct words. LDA takes a step back and tries to determine out what themes led to the creation of those papers in the first place, given a group of documents. Matrix factorization is a technique used in LDA. Any corpus (collection of documents) can be represented as a document-term matrix in vector space.
 
## Preparaing document - term matrix
To run any mathematical model on text corpus, it is a good practise to turn it into a matrix format. In the entire DT matrix, the LDA model looks for repeating term patterns. “Gensim,” a clean and attractive framework for handling text data, is one of many fantastic Python libraries for text mining activities.

