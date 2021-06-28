# VAEs-with-Conditioning

This repository will be used to store any code I use to implement VAEs with conditioning. This conditioning can be through unsupervised clustering or additional conditional information. Both methods will be explored. 

Two papers are key to the unsupervised clustering idea:
- Jiang Z, Zheng Y, Tan H, et al (2017) Variational deep embedding: An unsupervised generative approach to Clustering. IJCAI Int Jt Conf Artif Intell 0:1965–1972. https://doi.org/10.24963/ijcai.2017/273 (VaDE)
- Rao D, Visin F, Rusu AA, et al (2019) Continual unsupervised representation learning. Adv Neural Inf Process Syst 32: (CURL)

The difference between the two comes down to a mean-field approximation on $p(\mathbf{z}, \mathbf{y}\vert \mathbf{x})$, where VaDE assumes $\mathbf{z}$ and $\mathbf{y}$ are conditionally independent given $\mathbf{x}$.

![$p(\mathbf{z}, \mathbf{y}\vert \mathbf{x})$](http://www.sciweavers.org/tex2img.php?eq=1%2Bsin%28mc%5E2%29&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=)
