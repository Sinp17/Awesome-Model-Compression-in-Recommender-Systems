# Awesome-Model-Compression-in-Recommender-Systems
A collection of high-quality(newest) papers of model compression, particularly in the field of recommender systems. Due to the discreteness of input data and the characteristics of massive users and items in recommendation scenarios, the compression technics or  implementations are quite different from those commonly used in Computer Vision tasks. And this is the why this repro is created.

## Feature

> - Focus on compression skills on RS and NLP.
> - We propose two criteria to classify these papers.


### Parameter Pruning
1. [DeepLight: Deep Lightweight Feature Interactions for Accelerating CTR Predictions in Ad Serving](http://arxiv.org/abs/2002.06987)[WSDM 2021]
1. [UMEC: UNIFIED MODEL AND EMBEDDING COMPRES- SION FOR EFFICIENT RECOMMENDATION SYSTEMS](https://openreview.net/forum?id=BM---bH_RSh)[ICLR 2021]
3. [LEARNABLE EMBEDDING SIZES FOR RECOMMENDER SYSTEMS](https://arxiv.org/abs/2101.07577)[ICLR 2021]
4. [Single-Shot Embedding Dimension Search in Recommender System](https://arxiv.org/abs/2204.03281)[SIGIR 2022]
5. [OptEmbed: Learning Optimal Embedding Table for Click-through Rate Prediction](https://dl.acm.org/doi/10.1145/3511808.3557411)[CIKM 2022]

### Scalar Quantization/Binarization
1. [Learning Multi-Granular Quantized Embeddings for Large-Vocab Categorical Features in Recommender Systems](https://dl.acm.org/doi/10.1145/3366424.3383416)[WWW 2020]
1. [Learning Binarized Graph Representations with Multi-Faceted Quantization Reinforcement for Top-K Recommendation](http://arxiv.org/abs/2101.07577)[KDD 2022]
1. [Towards Low-Loss 1-Bit Quantization of User-Item Representations for Top-K Recommendation](http://arxiv.org/abs/2112.01944)[ArXiv]
4. [Post-Training 4-bit Quantization on Embedding Tables](https://arxiv.org/abs/1911.02079)[NIPS 2019]


## Product quantization
1. [Product Quantization for Nearest Neighbor Search](https://doi.org/10.1109/TPAMI.2010.57)
3. [Product Quantized Collaborative Filtering](https://ieeexplore.ieee.org/document/8950031/)[TKDE 2020]
2. [LightRec: A Memory and Search-Efficient Recommender System](https://dl.acm.org/doi/10.1145/3366423.3380151)[WWW 2020]
1. [Compositional Embeddings Using Complementary Partitions for Memory-Efficient Recommendation Systems](https://doi.org/10.1145/3394486.3403059)[KDD 2021]
5. [XLightFM: Extremely Memory-Efficient Factorization Machine](https://doi.org/10.1145/3404835.3462941)[SIGIR 2021]
6. [Distill-VQ: Learning Retrieval Oriented Vector Quantization By Distilling Knowledge from Dense Embeddings](http://arxiv.org/abs/2204.00185)[SIGIR 2022]
7. [Learning Elastic Embeddings for Customizing On-Device Recommenders](https://arxiv.org/abs/2211.14729)(KDD 2021)

## Embedding Factorization
1. [Fast and Memory-Efficient Tucker Decomposition for Answering Diverse Time Range Queries](https://doi.org/10.1145/3447548.3467290)[KDD 2021]
2. [TT-Rec: Tensor Train Compression for Deep Learning Recommendation Models](http://arxiv.org/abs/2101.11714)[MlSys 2021]
3. [Next Point-of-Interest Recommendation on Resource-Constrained Mobile Devices](https://dl.acm.org/doi/10.1145/3366423.3380170)[WWW 2020]
4. [On-Device Next-Item Recommendation with Self-Supervised Knowledge Distillation](http://arxiv.org/abs/2204.11091)[SIGIR 2022]

## Distillation
1. [Rocket Launching: A Universal and Efficient Framework for Training Well-Performing Light Net](http://arxiv.org/abs/1708.04106)[AAAI 2018]
1. [Ensembled CTR Prediction via Knowledge Distillation](https://doi.org/10.1145/3340531.3412704)[CIKM 2020]
1. [Ranking Distillation: Learning Compact Ranking Models With High Performance for Recommender System](https://doi.org/10.1145/3219819.3220021)[KDD 2018]
2. [Collaborative Distillation for Top-N Recommendation](https://arxiv.org/abs/1911.05276)[ICDM 2019]
4. [DE-RRD: A Knowledge Distillation Framework for Recommender System](https://doi.org/10.1145/3340531.3412005)[CIKM 2020]
1. [Bidirectional Distillation for Top-K Recommender System](http://arxiv.org/abs/2106.02870)[WWW 2021]
1. [ADER: Adaptively Distilled Exemplar Replay Towards Continual Learning for Session-Based Recommendation](https://doi.org/10.1145/3383313.3412218)[RecSys 2020]
2. [Topology Distillation for Recommender System](https://dl.acm.org/doi/10.1145/3447548.3467319)[KDD 2021]
3. [Interpolative Distillation for Unifying Biased and Debiased Recommendation](https://dl.acm.org/doi/10.1145/3477495.3532002)[SIGIR 2022]
4. [Unbiased Knowledge Distillation for Recommendation](https://arxiv.org/abs/2211.14729)[WSDM 2023]

## others
1. [Mixed Dimension Embeddings with Application to Memory-Efficient Recommendation Systems](http://arxiv.org/abs/1909.11810)[ArXiv 2019]
3. [Saec: Similarity-Aware Embedding Compression in Recommendation Systems](http://arxiv.org/abs/1903.00103)[ArXiv 2019]
1. [A Generic Network Compression Framework for Sequential Recommender Systems](http://arxiv.org/abs/2004.13139)[SIGIR 2020]
4. [NewsBERT: Distilling Pre-Trained Language Model for Intelligent News Application](http://arxiv.org/abs/2102.04887)[EMNLP 2021]

-----
This repo aims to provide the info for model compression research (especially in RS and NLP). Welcome to PR the works (papers, repositories) that are missed by the repo.





