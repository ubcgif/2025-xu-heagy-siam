# Leveraging neural fields for geophysical inverse problems

_Anran Xu and Lindsey Heagy_

Presented at SIAM MDS 2024

## Poster

![Poster](MDS24.png)

## Abstract

  The recent surge in test time learning (TTL) has garnered substantial attention from researchers, particularly in the context of incorporating machine learning algorithms into the inversion process. The deep image prior (DIP) method and coordinate-based representations (e.g., neural fields) have shown that neural networks, without any prior learning, can produce good inversion results. In this work, we will discuss the progress in utilizing neural fields in the geophysical inverse problems. Neural fields use neural networks to map a coordinate to the corresponding physical property value at that coordinate. We formulate the inverse problem in terms of the NN-weights, which allows us to take advantage of searching over the high-dimensional space.  Furthermore, parameterizing the inverse problems in a continuous setting naturally introduces smoothing effects. We integrate the neural fields into seismic tomography inversions and direct current resistivity inversions. The results show that this TTL approach can eliminate unwanted artifacts in the recovered subsurface physical property model caused by the sensitivity of the survey and physics. We also find that our results are better than the conventional inversion results in some cases in terms of the recovery of the boundaries and physical property values of the main targets. Our work illustrates that the inductive bias brought by a neural field can be beneficial in geophysical inversion.

---

