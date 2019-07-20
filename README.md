# hassanat-distance-checker
Analysis of the results of the Hassanat distance in K-NN algorithms.

A paper titled `Distance and Similarity Measures Effect on the Performance of K-Nearest Neighbor Classifier – A Review` available [here](https://arxiv.org/pdf/1708.04321.pdf) showed how a new distance metric called "hassanat" had very good results on a variety of ML problems, from over 50 metrics analysed and 28 differente datasets.

I formulated a hypothesis: One of the reasons the metric performed so well was due to non standardization of the data. If the data was standardized, other metrics would be as good, if not better than the hassanat metric.

What follows is a jupyter notebook of this hypothesis.
