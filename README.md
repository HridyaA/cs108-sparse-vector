# Differential Privacy - Sparse Vector Implementation

This project looked at correct and incorrect implementation of the sparse vector technique in differential privacy. 

The sparse vector technique (SVT) takes a stream of queries and a predefined public threshold T. It returns the identities (not values) of the first k queries that are likely larger than the threshold, and nothing else. No matter how many queries are passed to the Sparse Vector Technique, it has a fixed total privacy cost.

Research Papers:
* [Detecting Violations of Differential Privacy](https://arxiv.org/pdf/1805.10277.pdf)
* [Free Gap Information from the Differentially Private Sparse
Vector and Noisy Max Mechanisms](https://arxiv.org/pdf/1904.12773.pdf)
* [Differential Privacy and Machine Learning: A Survey and Review](https://arxiv.org/pdf/1412.7584.pdf?source=post_page---------------------------)
* [Differential Privacy: A Survey of Results](https://link.springer.com/chapter/10.1007/978-3-540-79228-4_1)

Other sources:
* [The Sparse Vector Technique](https://programming-dp.com/ch10.html)
