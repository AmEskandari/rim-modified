# rim-modified
This is modified verisin of rim: https://github.com/zwt233/RIM. I worked on this paper (https://arxiv.org/abs/2110.14854) in the statistical learning course seminar. In the original source code, they just simulated RIM-GCN, in this source code I also programmed source code for RIM-LP. in addition, I write descriptions and comments for better user understanding. The project has received a full score.

## My term Paper Abstract:
Mwork (GCN) and Label Propagation (LP), essage passing is the core of most graph models such as Graph Convolutional Netwhich usually require a large number of clean labeled data to smooth out the neighborhood over the graph. However, the labeling process can be tedious, costly, and error-prone in practice. "RIM" Algorithm offers a novel algorithm and architecture based on Influence maximization (both quantity and quality) assisted by the message-passing method. The quantity of influence measures how
much influence a labeled node does on an unlabeled node in a GRAPH, and quality dealing with honesty/trust of influence toward the right label. In this paper, I don’t aim to discuss the detail of the RIM algorithm, but I am willing to interpret details of written source code for algorithm simulation. I use two datasets "Cora" and "Citeseer". Rest of the paper is divided into 3 sections: in the first section, I explain "RIM" briefly, then I explain the details of
source code that is used for simulating "RIM", Also in the last section I interpret result of re-simulation. In this paper, I assume readers already is familiar with Graph, Graph Convolution Networks, Label Propagation, and Active Learning.

##Result:
I reported the main results to compare to Table 1 of the original paper. In Table 2 the oracle accuracy for both datasets is 0.7 which means error of labeling is 0.3. The budget size for Cora is 140 and for Citeseer is 120. Also in this table, the result of baselines are brought from the original paper. In the table, the "Model" is classifier algorithm and the "Methods" is the subset selector algorithm.

