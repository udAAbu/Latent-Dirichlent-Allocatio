# Latent-Dirichlent-Allocatio
Topic modelling using LDA

**Latent Dirichlet Allocation**, also known as LDA, is a popular topic modeling technique. As the name indicated, it helps to find latent topics in our document corpus. These topics are implicit and usually represented by some keywords. After finding these topics, LDA can help to classify documents to a particular topic.

LDA builds a **topic per document model** and **words per topic model**. In the topic per document model, each document is modeled as a multivariate distribution of topics, and in the words per topic model, each topic is modeled as a multivariate distribution of words.

Thanks to the excellent implementation of LDA in Gensim package, this notebook explores the applicaiton of LDA on the 20-Newsgroups dataset. This dataset contains about 11000 newsgroup posts from 20 different topics. 
