# Literature_Review_TTML
Papers related to my project - Bias in Brand Communication

# Papers Related to : Classification with Noisy labels
1.  Wang, Yaowei, et al. "Sentiment and emotion classification over noisy labels." Knowledge-Based Systems 111 (2016): 207-216.
https://www.sciencedirect.com/science/article/pii/S095070511630274X

Key Takeaways: Noise can be either due to difficult documents ( it is hard for humans to label such documents ) or due to careless taggers. They try to predict which documents have higher probability of being mistagged. They generate noise artificially and test their model against some other well-known classifiers like SVM. 


2. Sukhbaatar, Sainbayar, and Rob Fergus. "Learning from noisy labels with deep neural networks." arXiv preprint arXiv:1406.2080 2.3 (2014): 4. http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.749.1795&rep=rep1&type=pdf

Key Takeaways: They introduce an extra noise layer into the network which adapts the network outputs to match the noisy label distribution. The parameters of this noise layer can be estimated as part of the training process and involve simplemodifications to current training infrastructures for deep networks. Mostly for text data.
#Thought: Much of the robustness work is about image data and it is not clear how to adapt it to text

3. Sukhbaatar, Sainbayar, et al. "Training convolutional networks with noisy labels." arXiv preprint arXiv:1406.2080 (2014).
https://arxiv.org/pdf/1406.2080.pdf
Key Takeaways:

4. Simple Remedies :
Running experiments on Amazon Mechanical Turk- http://sjdm.org/~baron/journal/10/10630a/jdm10630a.pdf
Using multiple raters: https://dl.acm.org/doi/10.5555/2002472.2002490
