# Features

Pereval integrates both attribute-scoped and deep feature metrics under one package. Metrics can be used for 1) assessing distributional discrepancies between two sets of MIDI piano performances and 2) asssigning perceptual pseudo-ratings to individual performances.

**Attribute-scoped metrics:**
- Inter-set correlation
- Intra-set correlation
- KL Divergence

**Deep feature metrics:**
- Fréchet Music Distance (FMD)
- Kernel Music Distance (KMD)
- Kernel Performance Distance (KPD)

**Per-sample pseudo ratings:**
- Mahalanobis Distance
- Relative Mahalanobis Distance
- Marginal Mahalanobis Distance

Note that correlation, FMD, KMD, and KPD can also be used for per-sample evaluation.

Deep feature metrics are calculated using the embeddings from pretrained self-supervised symbolic music models ([Aria](https://github.com/EleutherAI/aria) and [CLaMP3](https://github.com/sanderwood/clamp3)). Pereval supports feature extraction from the Aria model. To integrate CLaMP3 embeddings, please install CLaMP3 separately.
