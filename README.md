# hassanat-distance-checker
Analysis of the results of the Hassanat distance in K-NN algorithms.

A paper titled `Distance and Similarity Measures Effect on the Performance of K-Nearest Neighbor Classifier – A Review` available [here](https://arxiv.org/pdf/1708.04321.pdf) showed how a new distance metric called "hassanat" had very good results on a variety of ML problems, from over 50 metrics analysed and 28 differente datasets.

I formulated a hypothesis: One of the reasons the metric performed so well was due to non standardization of the data. If the data was standardized, other metrics would be as good, if not better than the hassanat metric.

What follows is a ~~jupyter notebook of this hypothesis.~~ rough implementation of some very little code;

# UPDATE:

I originally formulated my hypothesis as a 2nd year undergratuate and due to having to hunt each individual dataset and not having much experience nor time, I halted work;

The original author got in touch and was kind enough to give me a update about their work:
``` (...) Your hypothesis is accurate, yes, we noted that in some previous papers, that doing normalization/standardization of the data makes Hassanat distance almost useless. (...) In my opinion, data normalization/standardization is a trick used by practitioners including myself to enhance machine learning results, but converting real-world data to another domain, particularly in the presence of outliers and noise affects the information that can be learned from data, and that exactly why we proposed Hassanat distance, so as to be able to learn from data without normalization/standardization. This motivates finding a distance metric that  is invariant to data scale, noise and outliers.```

There is also a update to their original paper [here](https://doi.org/10.1089/big.2018.0175);

I am happy that my original hypothesis makes sense and while I do slightly agree that learning a general metric would be interesting, I think it should be compared to metrics that have seen the data normalized, especially for a sensitive method such as K-NN;

It was very nice of the author to get in contact; If you came across this by any chance and have interest in the field, I would recommend getting in touch with [him](https://doi.org/10.1089/big.2018.0175).
