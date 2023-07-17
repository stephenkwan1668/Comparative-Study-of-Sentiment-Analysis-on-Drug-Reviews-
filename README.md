# Comparative Study of-Sentiment Analysis on Drug Reviews using Deep Learning Models and Embedding Techniques

This is a Thesis project at the Vrije Universiteit Amsterdam(Free University Amsterdam), under the supervision of assistant professor Ronald Siebes.



The aim of this thesis is to conduct a comparison study [1] of model performances, specifically by doing a three-class sentiment analysis (neutral, positive, or negative) by utilizing the models that have not yet been trained in the comparison study.

In this study, we intend to employ two pre-trained static word embedding techniques, namely the FastText and GloVe [2], which serve as the weight initializers for the embedding layer of the convolutional neural network [3]. Additionally, we will include ALBERT [4], a contextual embedding model that is considered the next generation of the BERT model [4], and explore whether the hybrid model ALBERT + Bi-LSTM (ALBERT is employed to create the contextual embedding which serves as the input for the Bi-LSTM layer) can match or exceed the performance of the BERT-LSTM model, which was identified as the best model among all models evaluated in the comparison study. In addition, we compare the best-performing model of this research to the best-performing model (BERT + Bi-LSTM) of the study that is being compared to. Furthermore, this study analyzes the impact on the model performance by employing the same pre-processed dataset of the comparison study, the dataset originates from the drugs.com [5] dataset, which serves as the foundation for the comparison study.



## References

1. [S. Vijayaraghavan and D. Basu. Sentiment Analysis in Drug Review using Supervised Machine Learning.](https://arxiv.org/pdf/2003.11643.pdf) 
2. [M. Wankhade and A. Rao and C. Kulkarni. A survey on sentiment analysis methods, applications and challenges.](https://link.springer.com/content/pdf/10.1007/s10462-022-10144-1.pdf) 
3. [J. Na and W. Kyauing and C. Khoo and S. Foo and Y. Chang and Y. Theng. Sentiment Classification of Drug Reviews Using a Rule-Based Linguistic Approach.](https://link.springer.com/content/pdf/10.1007/978-3-642-34752-8.pdf) 
4. [C. Colón-Ruiz and I. Segura-Bedmar. Comparing deep learning architectures for sentiment analysis on drug reviews.](https://www.sciencedirect.com/science/article/pii/S1532046420301672) 
5. [Felix Gräßer and Surya Kallumadi and Hagen Malberg and Sebastian Zaunseder. Drug Review Dataset (Drugs.com).](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29)







