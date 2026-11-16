---
layout: archive
title: "Research"
permalink: /research/
excerpt: "Statistical learning, uncertainty quantification, and Bayesian methods for scientific data."

author_profile: true
last_modified_at: 2026-11-16
---

My research develops statistical theory and computational methods for complex scientific data. Astronomy and space weather motivate much of this work, alongside collaborations in biology and epidemiology.

[Overview](#research-overview) · [By topic](#publications-by-research-topics) · [Preprints](#preprints-and-manuscripts) · [Publications](#publications-and-data-by-year) · [Data and tools](#data-and-forecasting-tools) · [Funding]({{ '/funding/' | relative_url }})

## Research overview

* **Tensor and spatiotemporal learning.** Structured models for reconstructing incomplete images and forecasting evolving spatial data, including tensor Gaussian processes, matrix autoregression, and efficient tensor completion.
* **Uncertainty quantification and probabilistic prediction.** Conformal methods, debiasing, and probabilistic models that quantify uncertainty in recovered observations and scientific forecasts.
* **Bayesian inference and latent-variable models.** Methods for model selection, prior sensitivity, instrument calibration, and inference with hidden states and heterogeneous populations.

The topical guide below connects these methods to scientific questions. Full citations, preprints, and reusable research outputs follow.

## Publications by Research Topics

### Astrostatistics

1. Instrument Calibration:
   * Statistical Methods - [Chen et al. (2019 JASA)](https://doi.org/10.1080/01621459.2018.1528978).
   * Astronomy Extensions - [Marshall et al. (2021 AJ)](https://doi.org/10.3847/1538-3881/ac230a).
   * Incorporating multiple bandpasses - [Das et al. (2026)](https://arxiv.org/abs/2611.18241).

2. Goodness-of-fit Assessment with High-order Asymptotics: [Li et al. (2025 preprint)](https://arxiv.org/abs/2510.03466), [Bonamente et al. (ApJ)](https://iopscience.iop.org/article/10.3847/1538-4357/ad9b1e/meta).

3. Solar Flare Forecasting:
   * Machine Learning Prediction - [Chen et al. (2019 SW)](https://doi.org/10.1029/2019SW002214), [Wang et al. (2020 ApJ)](https://doi.org/10.3847/1538-4357/ab89ac), [Sun et al. (2022 ApJ)](https://doi.org/10.1002/essoar.10508256.1), [Aktukmak et al. (2022 FASS)](https://doi.org/10.3389/fspas.2022.1040107), [Chen et al. (2023, Editorial Note)](https://doi.org/10.3389/fspas.2023.1121615), [Chen et al. (2024 Review Paper)](https://doi.org/10.1080/29979676.2024.2391688).
   * Interpreting LSTM Predictions - [Sun et al. (2019 preprint)](https://arxiv.org/abs/1912.12360).
   * Mixed LSTM for Flare Indicator and Intensity - [Jiao et al. (2020 SW)](https://doi.org/10.1029/2020SW002440).
   * Statistical Feature Construction - [Sun et al. (2021 SW)](https://doi.org/10.1002/essoar.10507540.1).
   * Tensor Contraction with Gaussian Process - [Sun et al. (2023 ICML)](https://proceedings.mlr.press/v202/sun23f.html).
   * Optimal Prediction of Extreme Events - [Verma et al. (2026 JTSA)](https://doi.org/10.1111/jtsa.12820).

### Data-Driven Approaches for Space Weather

1. Prediction Models for Solar Energetic Particles:
   * SEP Prediction with SMARP - [Kasapis et al. (2022 SW)](https://doi.org/10.1029/2021SW002842).
   * SEP reviews - [Whitman et al. (2023 ASR)](https://doi.org/10.1016/j.asr.2022.08.006), [Kasapis et al. (2026 preprint)](https://arxiv.org/abs/2606.19539).
   * SEPNET - [Yu et al. (2026 JGR-MLC)](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2026JH001247).
   * SEPNET-PRISM Model [Yu et al. (2026 SR)](https://www.nature.com/articles/s41598-026-66110-2).
   * SEPNET-PRISM Data [Yu et al. (2026 SD)](https://www.nature.com/articles/s41597-026-08552-x#citeas).
   * Real-time Forecasting - SEPNET-PRISM-R: [Live forecasts](https://mlsw.engin.umich.edu/apps/sepnet-prism), [Yu et al. (2026 preprint)](https://arxiv.org/abs/2610.28292).

2. Prediction Models for Geomagnetic Indices:
   * SYM-H - [Iong et al. (2022 SW)](https://doi.org/10.1029/2021SW002928).
   * Multivariate Functional Time Series - [Yu et al. (2026 preprint)](https://arxiv.org/abs/2606.14417).
   * Delta-B - [Iong et al. (2024 DSS)](https://www.tandfonline.com/doi/full/10.1080/26941899.2024.2383281).
   * Global Probabilistic Geomagnetic Perturbation Forecast - [Chen et al. (2025 SW)](https://doi.org/10.1029/2024SW004301), [Chen et al. (2026 JGR-MLC)](https://doi.org/10.1029/2026JH001299).

3. Imputation and Prediction for TEC Maps:
   * Video Imputation - [Sun et al. (2022 AOAS)](https://doi.org/10.1214/21-AOAS1541).
   * Uncertainty Quantification - [Sun and Chen (2026 JCGS)](https://doi.org/10.1080/10618600.2025.2554671), [Shang et al. (2026 preprint)](https://arxiv.org/abs/2604.10353).
   * Database - [Sun et al. (2023 SD)](https://doi.org/10.1038/s41597-023-02138-7).
   * Calibration - [Smirnova et al. (2026 SW)](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2026SW004978).
   * Prediction - [Wang et al. (2023 SW)](https://doi.org/10.1029/2023SW003494), [Sun et al. (Statistica Sinica, forthcoming)](https://doi.org/10.5705/ss.202025.0029).

4. Data Assimilation and Uncertainty Quantification:
   * [Jivani et al. (2023 SW)](https://doi.org/10.1029/2022SW003262).
   * GeoDGP: [Live forecasts](https://csem.engin.umich.edu/GeoDGP/), [Chen et al. (2025 SW)](https://doi.org/10.1029/2024SW004301), [Chen et al. (2026 JGR-MLC)](https://doi.org/10.1029/2026JH001299).

### Statistical Methodology

1. Prior Influence in Bayesian Inference: [Jones et al. (2022 BA)](https://doi.org/10.1214/21-BA1217), [Chen et al. (2020 preprint)](https://arxiv.org/abs/2001.08336).

2. Matrix Autoregressive Model with Global Exogenous Predictors: [Sun et al. (Statistica Sinica, forthcoming)](https://doi.org/10.5705/ss.202025.0029).

3. Finite Mixture Models -- Order Selection and Misspecification: [Chen et al. (2025 JMLR)](https://jmlr.org/papers/v26/23-0343.html).

4. Optimal Prediction of Extreme Events: [Verma et al. (2026 JTSA)](https://doi.org/10.1111/jtsa.12820).

5. Efficient Tensor Completion: [Li et al. (2025 preprint)](https://arxiv.org/abs/2505.11261).

6. Conformal Tensor Completion: [Sun and Chen (2026 JCGS)](https://doi.org/10.1080/10618600.2025.2554671).

7. Online and Adaptive Tensor Learning: [Li et al. (2026 AOS)](https://doi.org/10.1214/25-AOS2588), [Qin and Chen (2026 preprint)](https://arxiv.org/abs/2606.10085).

8. Learning with Synthetic Data: [Tian et al. (2026 NeurIPS)](https://neurips.cc/virtual/2026/loc/sydney/poster/151392).

9. Local Interaction Autoregressive Models: [Li and Chen (Statistica Sinica, forthcoming)](https://doi.org/10.5705/ss.202025.0419).

10. Deep Learning for Compression: [Li, Chen, and Kim (2020 IEEE TC)](https://ieeexplore.ieee.org/document/9183947), [Li and Chen (2020 IEEE TC)](https://doi.org/10.1109/TCOMM.2019.2950714).


### Applied Statistics in Biological Sciences and Epidemiology

1. Biological Sciences: [Chen et al. (2016 JASA)](https://doi.org/10.1080/01621459.2016.1140050), [Choi et al. (2020 GB)](https://doi.org/10.1186/s13059-020-02103-2), [Mei et al. (2021 BiB)](https://doi.org/10.1093/bib/bbaa135), [Du et al. (2025 preprint)](https://doi.org/10.1101/2025.02.23.639769).

2. Epidemiology: [Zhao et al. (2019 IJE)](https://doi.org/10.1093/ije/dyz142), [Trangucci et al. (2023 AOAS)](https://doi.org/10.1214/22-AOAS1711), [Trangucci et al. (preprint)](https://arxiv.org/abs/2211.16502), [Iong et al. (2024 AOAS)](https://doi.org/10.1214/23-AOAS1816), [Trangucci et al. (preprint)](https://arxiv.org/abs/2404.04398).

## Preprints and manuscripts

Preprint dates may differ from the publication year of a later journal article.

\* indicates a corresponding author in the lists below.

1. J. Shang, J. Li, **Y. Chen**\*, *Uncertainty Quantification for Noisy Low-tubal-rank Tensor Completion*, preprint (2026). [[arXiv](https://arxiv.org/abs/2604.10353)].
2. Y. Yu, **Y. Chen**\*, L. Zhao, K. Whitman, W. Manchester, T. Gombosi, *Real-Time 24-hour Ahead Forecasting of Solar Energetic Particle Events with SEPNET-PRISM-R*, preprint (2026). [[arXiv](https://arxiv.org/abs/2610.28292)].
3. J. Li, J. Shang, and **Y. Chen**, *Fourier Low-rank and Sparse Tensor for Efficient Tensor Completion*, preprint (2025). [[arXiv](https://arxiv.org/abs/2505.11261)].
4. X. Li, **Y. Chen**\*, X.-L. Meng, D. van Dyk, M. Bonamente, V. Kashyap (2025), *Making high-order asymptotics practical: correcting goodness-of-fit test for astronomical count data*, preprint. [[arXiv](https://arxiv.org/abs/2510.03466)].
5. R. Trangucci, **Y. Chen**, J. Zelner, *Vaccine efficacy for binary post-infection outcomes under misclassification without monotonicity*, submitted. [[arXiv](https://arxiv.org/abs/2211.16502)].
6. W. Liu, I. Ibenaz, **Y. Chen**, A. Agrawal, *Transitory Sustainability Effects of Behavioral Changes: Short-Term Benefits of COVID-19 Lockdowns Reversed Over Time, Resulting in More Wildfires in the Amazon*, submitted. [[SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4438234)]
7. R. Trangucci, J. Contreras, J. Zelner, **Y. Chen**, *Bayesian Methods for Cumulative Exposure to Extensive Environmental Health Hazards: A Bayesian Inverse Perspective*, [[arXiv](https://arxiv.org/abs/2404.04398)].
8. Y. Ke, X. Huang, O. Coddington, **Y. Chen**, *Matrix Factorization-Based Solar Spectral Irradiance Missing Data Imputation with Uncertainty Quantification*, [[arXiv](https://arxiv.org/abs/2508.04074)]. Curated data based on this work: The Synthetic SSI Data Interpolated Based on CMIP6 SSI Data [Data set], University of Michigan - Deep Blue Data, [[Data](https://doi.org/10.7302/38cw-1j08)].
9. Y. Song, K. Zhu, **Y. Chen**, A. Stefanski, R. Bermudez, R. A. Montgomery, P. B. Reich, *Warming makes boreal species grow earlier but not always taller*, [[bioRxiv](https://www.biorxiv.org/content/10.64898/2025.11.30.691420v1)].
10. K. Hu, K. Jin, V. Verma, W. Liu, W. Manchester, L. Zhao, T. Gombosi, **Y. Chen**\*, *Data Quality Issues in Flare Prediction using Machine Learning Models*, [[arXiv](https://arxiv.org/abs/2512.13417)].
11. M. Aguirre, W. Sun, **Y. Chen**, J. Jin, *Automatic Identification of Driving Maneuver Patterns Using a Robust Hidden Semi-Markov Model*, [[SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4410473)]
12. S. Das, **Y. Chen**, H. Marshall, V. Kashyap, D. van Dyk, *Extended Bayesian Estimation for In-flight Calibration of Space-based Instruments*, [[arXiv](https://arxiv.org/abs/2611.18241)].
13. Y. Yu, S. Zou, T. Pulkkinen, **Y. Chen**, *Stable Multivariate Functional Time Series Prediction for Major Geomagnetic Indices*, preprint (2026). [[arXiv](https://arxiv.org/abs/2606.14417)].
14. Z. Qin, **Y. Chen**, *Structured Adaptive Tensor Learning for Streaming and Dynamic Data*, preprint (2026). [[arXiv](https://arxiv.org/abs/2606.10085)].
15. S. Kasapis et al., *Review of Machine Learning Models for Solar Energetic Particle Prediction*, preprint (2026). [[arXiv](https://arxiv.org/abs/2606.19539)].
16. N. Du, **Y. Chen**, Y. Qian, *BayesFit: Enhancing Experimental Fitting Accuracy with Bayesian Methods for Undersampled Data*, preprint (2025). [[bioRxiv](https://doi.org/10.1101/2025.02.23.639769)].
17. **Y. Chen**, R. Gong, M. Xie, *Geometric Conditions for the Discrepant Posterior Phenomenon and Connections to Simpson’s Paradox*, preprint (2020; revised 2022). [[arXiv](https://arxiv.org/abs/2001.08336)].
18. H. Sun, W. Manchester, Z. Jiao, X. Wang, **Y. Chen**, *Interpreting LSTM Prediction on Solar Flare Eruption with Time-series Clustering*, preprint (2019; revised 2020). [[arXiv](https://arxiv.org/abs/1912.12360)].

## Publications and data by year

Also available at my [Google Scholar](https://scholar.google.com/citations?user=ycbIaucAAAAJ&hl=en) and [ResearchGate](https://www.researchgate.net/profile/Yang-Chen-202) pages. Journal articles are grouped by their final issue year when available; this may differ from the year of online publication.

### Forthcoming journal articles

Accepted articles awaiting publication in a final journal issue.

1. J. Li\*, **Y. Chen**, *Local Interaction Autoregressive Model for High Dimension Time Series Data*, Statistica Sinica, forthcoming. [[Journal](https://doi.org/10.5705/ss.202025.0419)], [[arXiv](https://arxiv.org/abs/2511.09542)].
2. H. Sun, Z. Shang, **Y. Chen**\*, *Matrix Autoregressive Model with Vector Time Series Covariates for Spatiotemporal Data*, Statistica Sinica, forthcoming. [[Journal](https://doi.org/10.5705/ss.202025.0029)], [[arXiv](https://arxiv.org/abs/2305.15671)].

### 2026

1. Z. Tian, K. Jin, **Y. Chen**, T. Lee, *Risk-guided Estimation-aware Acceptance for Learning with Synthetic Data*, NeurIPS, 2026. [[Conference](https://neurips.cc/virtual/2026/loc/sydney/poster/151392)].
2. J. Li, J. Cai, **Y. Chen**, D. Xia, *Online Tensor Learning: Computational and Statistical Trade-offs, Adaptivity and Optimal Regret*, Annals of Statistics, 54(3), 1153–1177, 2026. [[Journal](https://doi.org/10.1214/25-AOS2588)], [[arXiv](https://arxiv.org/abs/2306.03372)].
3. H. Sun, **Y. Chen**\*, *Conformalized Tensor Completion with Riemannian Optimization*, Journal of Computational and Graphical Statistics, 35(2), 594–605, 2026. [[Journal](https://doi.org/10.1080/10618600.2025.2554671)], [[arXiv](https://arxiv.org/abs/2405.00581)].
4. V. Verma, S. Stoev, **Y. Chen**, *On the Optimal Prediction of Extreme Events in Heavy-Tailed Time Series With Applications to Solar Flare Forecasting*, Journal of Time Series Analysis, 47(1), 25–42, 2026. [[Journal](https://doi.org/10.1111/jtsa.12820)], [[arXiv](https://arxiv.org/abs/2407.11887)].
5. M. Smirnova, S. Zou, G. Kwon, H. Liu, **Y. Chen**, *Calibration and Fusion of GOLD-Inferred TEC Data with Ground-based TEC*, Space Weather, 24(6), e2026SW004978, 2026. [[Journal](https://doi.org/10.1029/2026SW004978)].
6. H. Chen, G. Toth, **Y. Chen**, S. Zou, and X. Huan, *Improving Geomagnetic Perturbation Forecasts in the Southern Hemisphere via Kernel-Based Encoding of Mirror Symmetry*, Journal of Geophysical Research: Machine Learning and Computation, 3(4):e2026JH001299, 2026. [[Journal](https://doi.org/10.1029/2026JH001299)], [[Preprint](https://essopenarchive.org/doi/full/10.22541/essoar.176297322.20727195)].
7. Y. Liu, Y. Song, W. Weaver, K. Shedden, **Y. Chen**, S. Smith, K. Zhu, *Dominance of plasticity in wind-pollinated trees flowering time response to temperature*, Ecology, [[bioRxiv](https://www.biorxiv.org/content/10.1101/2025.08.26.672405v1)].
8. Y. Yu, **Y. Chen**\*, L. Zhao, K. Whitman, W. Manchester, T. Gombosi (2026), *Solar Energetic Particle Forecasting with Multi-Task Deep Learning: SEPNet*, Journal of Geophysical Research: Machine Learning and Computation, [[Journal](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2026JH001247)].
9. Y. Yu, **Y. Chen**\*, L. Zhao, K. Whitman, W. Manchester, T. Gombosi, *Realtime forecasting of solar energetic particle event and proton flux using multi-source solar observations and multi-task deep learning*, Scientific Reports, [[Journal](https://www.nature.com/articles/s41598-026-66110-2)].
10. Y. Yu, **Y. Chen**\*, L. Zhao, K. Whitman, W. Manchester, T. Gombosi, *A multi-source dataset for solar energetic particle forecasting*, Scientific Data, [[Journal](https://www.nature.com/articles/s41597-026-08552-x)].

### 2025

1. H. Chen, N. Sachdeva, Z. Huang, B. van der Holst, W. Manchester IV, A. Jivani, S. Zou, **Y. Chen**, X. Huan, G. Toth, *Decent Estimate of CME Arrival time from a Data-assimilated Ensemble in the Alfvén Wave Solar atmosphere Model (DECADE-AWSoM)*, Space Weather, 23.1 (2025): e2024SW004165. [[Journal](https://doi.org/10.1029/2024SW004165)].
2. **Y. Chen**, C.-D. Fuh, C.-L. Kao, *Determine the Number of States in Hidden Markov Models via Marginal Likelihood*, Journal of Machine Learning Research, 26(58):1−59, 2025. [[Journal](https://jmlr.org/papers/v26/23-0343.html)], [[arXiv](https://arxiv.org/abs/2405.12343)].
3. **Y. Chen** (2025), Discussion on “Poisson-FOCuS: An Efficient Online Method for Detecting Count Bursts with Application to Gamma Ray Burst Detection” by Ward, Dilillo, Eckley, and Fearnhead, Journal of the American Statistical Association, 120(549), 26–30. [[Journal](https://doi.org/10.1080/01621459.2024.2402961)].
4. M. Bonamente, **Y. Chen**, D.  Zimmerman, *Maximum–likelihood Regression with Systematic Errors for Astronomy and the Physical Sciences: I. Methodology and Goodness–of–fit Statistic of Poisson Data*, The Astrophysical Journal, 980, no. 1 (2025): 139. [[Journal](https://iopscience.iop.org/article/10.3847/1538-4357/ad9b1e/meta)], [[arXiv](https://arxiv.org/abs/2407.12132)].
5. H. Chen, G. Toth, **Y. Chen**, S. Zou, X. Huan, *GeoDGP: Global Probabilistic Geomagnetic Perturbation Forecasting using Deep Gaussian Process*, Space Weather 23, no. 6 (2025): e2024SW004301. [[Journal](https://doi.org/10.1029/2024SW004301)].


### 2024

1. B. Viet Do, **Y. Chen**\*, L. Nguyen, W. Manchester, *Uncovering Heterogeneity of Solar Flare Mechanism with Mixture Models*, Frontiers in Astronomy and Space Sciences 11 (2024): 1229092. [[arXiv](https://arxiv.org/abs/2401.14345)], [[Journal](https://www.frontiersin.org/journals/astronomy-and-space-sciences/articles/10.3389/fspas.2024.1229092/full)].
2. D. Iong, M. McAnear, Y. Qu, S. Zou, G. Toth, **Y. Chen**\* (2024), *Sparse Variational Contaminated Noise Gaussian Process Regression with Applications in Geomagnetic Perturbations Forecasting*, Data Science in Science, Volume 3 Issue 1. [[arXiv](https://arxiv.org/abs/2402.17570)], [[Journal](https://www.tandfonline.com/doi/full/10.1080/26941899.2024.2383281)].
3. D. Iong, Q. Zhao, and **Y. Chen** (2024), *A Latent Mixture Model for Heterogeneous Causal Mechanisms in Mendelian Randomization*, Annals of Applied Statistics, Vol. 18, No. 2, 966-990. [[Journal](https://doi.org/10.1214/23-AOAS1816)], [[arXiv](https://arxiv.org/abs/2007.06476)].
4. **Y. Chen**, W. Manchester, M. Jin, A. Pevtsov, *Solar Imaging Data Analytics: A Selective Overview of Challenges and Opportunities*, Statistics and Data Science in Imaging (2024). [[arXiv](https://arxiv.org/abs/2405.12331)], [[Journal](https://doi.org/10.1080/29979676.2024.2391688)].
5. H. Tak, **Y. Chen**, V. Kashyap, K. Mandel, X.-L. Meng, A. Siemiginowska, D. van Dyk, *Statistical Maxims for Sound Astronomical Data Analysis*, The Astrophysical Journal Supplement Series, 275(2), 30. [[Journal](https://iopscience.iop.org/article/10.3847/1538-4365/ad8440/meta)]


### 2023

1. K. Whitman et al., *Review of Solar Energetic Particle Models*, Advances in Space Research, 72(12), 5161–5242, 2023. [[Journal](https://doi.org/10.1016/j.asr.2022.08.006)].
2. **Y. Chen**\*, S. Maloney, E. Camporeale, X. Huang, Z. Zhou, *Editorial: Machine Learning and Statistical Methods for Solar Flare Predictions*, Frontiers in Astronomy and Space Sciences, Sec. Stellar and Solar Physics, Volume 10 - 2023. [[Journal](https://doi.org/10.3389/fspas.2023.1121615)]
3. H. Sun, **Y. Chen**, S. Zou, J. Ren, Y. Chang, Z. Wang, A. Coster, *Complete Global Total Electron Content Map Dataset based on a Video Imputation Algorithm VISTA*, Scientific Data, 10:236, 2023. [[Journal](https://doi.org/10.1038/s41597-023-02138-7)]
4. H. Sun, W. Manchester, M. Jin, Y. Liu, **Y. Chen**\*, *Tensor Gaussian Process with Contraction for Multi-Channel Imaging Analysis*, Proceedings of the 40th International Conference on Machine Learning, PMLR 202:32913-32935, 2023. [[Proceedings](https://proceedings.mlr.press/v202/sun23f.html)]
5. H. Sun, J. Ren, **Y. Chen**, S. Zou, *VISTA TEC database [Data set]*, University of Michigan - Deep Blue Data, 2023. [[Data](https://doi.org/10.7302/vb27-ez24)]
6. R. Trangucci, **Y. Chen**, J. Zelner, *Modeling Racial/Ethnic Differences in COVID-19 Incidence with Covariates Subject to Nonrandom Missingness*, Annals of Applied Statistics, Vol. 17, No. 4, 2723-2758, 2023. [[Journal](https://doi.org/10.1214/22-AOAS1711)]
7. A. Jivani, N. Sachdeva, Z. Huang, **Y. Chen**, B. van der Holst, W. Manchester, D. Iong, H. Chen, S. Zou, X. Huan, G. Toth, *Global Sensitivity Analysis and Uncertainty Quantification for Background Solar Wind using the Alfven Wave Solar Atmosphere Model*, Space Weather 21.1, 2023: e2022SW003262. [[Journal](https://doi.org/10.1029/2022SW003262)]
8. Z. Wang, S. Zou, H. Sun, **Y. Chen**, *Forecast Global Ionospheric TEC: Apply Modified U-Net on VISTA TEC Dataset*, Space Weather 21, no. 8 (2023): e2023SW003494. [[Journal](https://doi.org/10.1029/2023SW003494)]


### 2022

1. H. Sun, Z. Hua, J. Ren, S. Zou, Y. Sun and **Y. Chen**\*. *Matrix Completion Methods for the Total Electron Content Video Reconstruction*, Annals of Applied Statistics 16(3), 1333-1358, 2022. [[Journal](https://doi.org/10.1214/21-AOAS1541)]
2. Z. Sun, M. Bobra, X. Wang, Y. Wang, H. Sun, T. Gombosi, **Y. Chen**, A. Hero. *Predicting Solar Flares Using CNN and LSTM on Two Solar Cycles of Active Region Data*, The Astrophysical Journal, 931(2), 2022. [[Journal](https://doi.org/10.1002/essoar.10508256.1)]
3. M. Aktukmak, Z. Sun, M. Bobra, T. I. Gombosi, W. Manchester, **Y. Chen**, A. O. Hero. *Incorporating Polar
Field Data for Improved Solar Flare Prediction*, Frontiers in Astronomy and Space Sciences, 21 December 2022, Sec. Stellar and Solar Physics, Volume 9 - 2022. [[Journal](https://doi.org/10.3389/fspas.2022.1040107)]
4. S. Kasapis, L. Zhao, **Y. Chen**, X. Wang, M. Bobra, T. I. Gombosi. *Interpretable
Machine Learning to Forecast SEP Events for Solar Cycle 23*, Space Weather, 20.2, 2022. [[Journal](https://doi.org/10.1029/2021SW002842)]
5. D. Iong, **Y. Chen**, G. Toth, S. Zou, T. Pulkkinen, J. Ren, E. Camporeale, T. Gombosi, *New Findings From Explainable SYM‐H Forecasting Using Gradient Boosting Machines*, Space Weather, 20(8), p.e2021SW002928, 2022. [[Journal](https://doi.org/10.1029/2021SW002928)]
6. D. E. Jones, R. N. Trangucci, **Y. Chen**\*. *Quantifying Observed Prior Impact*, Bayesian Analysis, 17(3), 737-764, 2022. [[Journal](https://doi.org/10.1214/21-BA1217)]

### 2021

1. W. Mei, Z. Jiang, **Y. Chen**, L. Chen, A. Sancar, Y. Jiang, *Genome-wide Circadian Rhythm Detection Methods: Systematic Evaluations and Practical Guidelines*, Briefings in Bioinformatics, 22(3), bbaa135, 2021. [[Journal](https://doi.org/10.1093/bib/bbaa135)].
2. H. Sun, W. B. Manchester IV, **Y. Chen**\*. *Improved and Interpretable Solar Flare Predictions with Spatial and Topological Features of the Polarity-inversion-line Masked Magnetograms*, Space Weather, 19, e2021SW002837, 2021. [[Journal](https://doi.org/10.1002/essoar.10507540.1)]
3. A. Farahi, **Y. Chen**. *TATTER: A Hypothesis Testing Tool for Multi-dimensional Data*, Astronomy and Computing, 34, 2021. [[Journal](https://doi.org/10.1016/j.ascom.2020.100445)]
4. H. Marshall, **Y. Chen**, J. Drake, M. Guainazzi, V. L. Kashyap, X.-L. Meng, P. Plucinsky, P. Ratzlaff, D. van Dyk, X. Wang. *Concordance: In-flight Calibration of X-ray Telescopes without Absolute References*, The Astronomical Journal, 162(6):254, 2021. [[Journal](https://doi.org/10.3847/1538-3881/ac230a)]
5. W. Ma, Z. Wang, Y. Zhang, N. Magee, **Y. Chen**, C. Zang. *BARTweb: a Web Server for Transcription Factor Association Analysis*, NAR Genomics and Bioinformatics, 3(2), 2021. [[Journal](https://doi.org/10.1093/nargab/lqab022)]
6. S. Zou, J. Ren, Z. Wang, H. Sun, **Y. Chen**. *Impact of Storm-Enhanced Density (SED) on Ion Upflow Fluxes During Geomagnetic Storm*, Frontiers in Astronomy and Space Sciences, 23, 2021. [[Journal](https://doi.org/10.3389/fspas.2021.746429)]

### 2020

1. Q. Li, **Y. Chen**, Y. Kim, *Compression by and for Deep Boltzmann Machines*, IEEE Transactions on Communications, 68(12), 7498–7510, 2020. [[Journal](https://ieeexplore.ieee.org/document/9183947)].
2. Q. Li, **Y. Chen**, *Rate Distortion via Deep Learning*, IEEE Transactions on Communications, 68(1), 456–465, 2020. [[Journal](https://doi.org/10.1109/TCOMM.2019.2950714)].
3. Z. Jiao, H. Sun, X. Wang, W. Manchester, T. Gombosi, A. Hero, **Y. Chen**\*. *Solar Flare Intensity Prediction with Machine Learning Models*, Space Weather, 18(7), 2020. [[Journal](https://doi.org/10.1029/2020SW002440)]
4. X. Wang, **Y. Chen**, G. Toth, W. B. Manchester, T. I. Gombosi, A. O. Hero, Z. Jiao, H. Sun, M. Jin, Y. Liu, *Predicting Solar Flares with Machine Learning: Investigating Solar Cycle Dependence*, The Astrophysical Journal, 895(3), 2020. [[Journal](https://doi.org/10.3847/1538-4357/ab89ac)]
5. R. Trangucci, D. Hansen, **Y. Chen**, *Contributed Discussion for "On a Class of
Objective Priors from Scoring Rules (with discussion)"*, Bayesian Analysis, 15(4), 1345-1423, 2020. [[Journal](https://doi.org/10.1214/19-BA1187)]
6. K. Choi, **Y. Chen**, D. A. Skelly, G. A. Churchill, *Bayesian Model Selection Reveals Biological Origins of Zero Inflation in Single-cell Transcriptomics*, Genome Biology 21, 2020. [[Journal](https://doi.org/10.1186/s13059-020-02103-2)]
7. J. Ren, J. Lu, S. Zou, N. Giertych, **Y. Chen**, R. H. Varney, *Statistical Study of Ion Upflow and Downflow Observed by the Poker Flat Incoherent Scatter Radar (PFISR)*, Journal of Geophysical Research: Space Physics,  125(10), 2020. [[Journal](https://doi.org/10.1029/2020JA028179)]
8. A. Farahi, D. Nagai, and **Y. Chen.** *PoPE: A Population-based Approach to
Model the Spatial Structure of Astronomical Systems*, The Astronomical Journal
161(1), 2020. [[Journal](https://doi.org/10.3847/1538-3881/abc630)]


### 2019

1. **Y. Chen**, X.-L. Meng, X. Wang, D. A. van Dyk, H. L. Marshall, V. L. Kashyap. *Calibration Concordance for Astronomical Instruments via Multiplicative Shrinkage*, Journal of the American Statistical Association, 114(527), 1018-1037, 2019. [[Journal](https://doi.org/10.1080/01621459.2018.1528978)]
2. F. Seeger, A. Little, **Y. Chen**, T. Woolf, H. Cheng and J. Mitchell. *Feature Design for Protein Interface Hotspots Using KFC2 and Rosetta*, Research in Data Science (Springer), 177-197, 2019. [[Book chapter](https://doi.org/10.1007/978-3-030-11566-1_8)]
3. Q. Zhao, **Y. Chen**, J. Wang, and D. S. Small. *Powerful Genome-wide Design and Robust Statistical Inference in Two-sample Summary-data Mendelian Randomization*, International Journal of Epidemiology, 48(5), 1478-1492, 2019. [[Journal](https://doi.org/10.1093/ije/dyz142)]
4. **Y. Chen**, W.B. Manchester, A.O. Hero, G. Toth, B. DuFumier, T. Zhou, X. Wang, H. Zhu, Z. Sun, and T.I. Gombosi, *Identifying Solar Flare Precursors Using Time Series of SDO/HMI Images and SHARP Parameters*, Space Weather 17(10), 1404-1426, 2019. [[Journal](https://doi.org/10.1029/2019SW002214)]

### 2018 and earlier

1. **Y. Chen**, K. Shen, S. Shan, and S. C. Kou. *Analyzing Single-molecule Protein Transportation Experiments via Hierarchical Hidden Markov Models*, Journal of the American Statistical Association 111(515), 951-966, 2016. [[Journal](https://doi.org/10.1080/01621459.2016.1140050)]
2. H. Bavli, **Y. Chen**. *Shrinkage Estimation in the Adjudication of Civil Damage Claims*, Review of Law & Economics, 13(2), 2017. [[Journal](https://doi.org/10.1515/rle-2015-0010)]
3. S. Yang, **Y. Chen**, E. Bernton, and J. S. Liu. *On Parallelizable Markov Chain Monte
Carlo Algorithms with Waste-recycling*, Statistics and Computing 28(5), 1073-1081, 2018. [[Journal](https://doi.org/10.1007/s11222-017-9780-4)]


## Data and forecasting tools

| Resource | Description | Access |
| --- | --- | --- |
| **SEPNET-PRISM-R** | Probabilistic forecasts of solar energetic particle events, issued hourly for the following 24 hours. | [Live forecasts](https://mlsw.engin.umich.edu/apps/sepnet-prism) · [Preprint](https://arxiv.org/abs/2610.28292) |
| **GeoDGP** | Probabilistic forecasting of global geomagnetic perturbations. | [Live forecasts](https://csem.engin.umich.edu/GeoDGP/) · [Journal article](https://doi.org/10.1029/2024SW004301) |
| **VISTA** | Global total electron content maps reconstructed from incomplete observations. | [Dataset](https://doi.org/10.7302/vb27-ez24) · [Journal article](https://doi.org/10.1038/s41597-023-02138-7) |
| **Solar spectral irradiance** | Synthetic SSI data interpolated from CMIP6 SSI data. | [Dataset](https://doi.org/10.7302/38cw-1j08) · [Preprint](https://arxiv.org/abs/2508.04074) |
| **SEPNET-PRISM data** | A dataset combining multiple sources of solar observations for SEP forecasting. | [Dataset paper](https://www.nature.com/articles/s41597-026-08552-x) |

## Research support and statement

[Research funding]({{ '/funding/' | relative_url }}) · [Research statement (2024)](https://drive.google.com/file/d/11NPVF0y14iWjwgNJia41TBS0tEKpG9XA/view?usp=drive_link)
