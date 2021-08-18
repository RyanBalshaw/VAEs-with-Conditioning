# VAEs-with-Conditioning

This repository will be used to store any code I use to implement VAEs with conditioning. This conditioning can be through unsupervised clustering or additional conditional information. Both methods will be explored. 

Two papers are key to the unsupervised clustering idea:
- Jiang Z, Zheng Y, Tan H, et al (2017) Variational deep embedding: An unsupervised generative approach to Clustering. IJCAI Int Jt Conf Artif Intell 0:1965–1972. https://doi.org/10.24963/ijcai.2017/273 (VaDE)
- Rao D, Visin F, Rusu AA, et al (2019) Continual unsupervised representation learning. Adv Neural Inf Process Syst 32: (CURL)

The difference between the two comes down to a mean-field approximation on p(z, y|x), where VaDE assumes z and y are conditionally independent given x.

I have also implemented an Adversarial Auto-Encoder (AAE) and REPGAN. These scripts are placed in two separate notebooks.
- Makhzani A, Shlens J, Jaitly N, et al (2015) Adversarial autoencoders. Arxiv:151105644
- Zhou Y, Gu K, Huang T (2019) Unsupervised Representation Adversarial Learning Network: From Reconstruction to Generation. Proc Int Jt Conf Neural Networks 2019-July: https://doi.org/10.1109/IJCNN.2019.8852395

REPGAN does not have the pairwise loss yet, but I can add it in.

This repo implements each of these methods in isolation, so that they can be run independently (just check this before final commits).


