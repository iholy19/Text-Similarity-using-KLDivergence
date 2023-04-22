# Text-Similarity-using-KLDivergence
This model helps in finding similarity between 2 sentences using KL Divergence and Laplace smoothing(for empty tokens). The closer the value to zero, the more is the similarity

### About KL Divergence
Given 2 data distributions or probability distributions, KL divergence is used in finding how much distribution 1 differs from distribution 2. 
It is calculated using the below formula,

KL(p,q) = sum(p(x_i) * log(p(x_i)/q(x_i)))
Here we have used spacy and nltk libraries to preprocess the sentences and create a data distribution. Then we applied the KL divergence on the 2 distributions of the sentences

### Properties of KL divergence

It does not say about the distance between 2 distributions
KL(P,Q) ≠ KL(Q,P)
The KL(P,Q) is defined only when at any x, p(x) exists and ≠ 0
