# Sentiment Analysis

##  Data:
This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well. Raw text and already processed bag of words formats are provided. See the README file contained in the release for more details.
<br>The Dataset of 50,000 movie reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been preprocessed, and each review is encoded as a sequence of word indexes (integers). For convenience, the words are indexed by their frequency in the dataset, meaning the word that has index 1 is the most frequent word. Use the first 20 words from each review to speed up training, using a max vocab size of 10,000.
<br>As a convention, "0" does not stand for a specific word, but instead is used to encode any unknown word
## Data reference: 
https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz

## Citation:
```
@InProceedings{maas-EtAl:2011:ACL-HLT2011,
  author    = {Maas, Andrew L.  and  Daly, Raymond E.  and  Pham, Peter T.  and  Huang, Dan  and  Ng, Andrew Y.  and  Potts, Christopher},
  title     = {Learning Word Vectors for Sentiment Analysis},
  booktitle = {Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies},
  month     = {June},
  year      = {2011},
  address   = {Portland, Oregon, USA},
  publisher = {Association for Computational Linguistics},
  pages     = {142--150},
  url       = {http://www.aclweb.org/anthology/P11-1015}
}
```
Note:
This project was done as part of the assignment from GreatLearning’s Post Graduate Program for AI/ Machine Learning [https://www.mygreatlearning.com/artificial-intelligence/courses/pg-program-online-artificial-intelligence-machine-learning]
## Key asks:
•	Predict the number of positive and negative reviews based on sentiments by using different classification models.
