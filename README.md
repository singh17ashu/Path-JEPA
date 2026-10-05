# Path-JEPA — project page



**Paper:** [Springer (ECCV 2026)](https://link.springer.com/chapter/10.1007/978-3-032-37258-1_7)

> **Code coming soon.** The official implementation of Path-JEPA (training, evaluation, and pretrained checkpoints) is being prepared for release and will be published shortly. Watch or star this repository to be notified when it's available.

## Abstract

Self-supervised learning (SSL) has become a leading paradigm for skeleton-based action recognition, yet the choice of prediction target remains a central limitation. Existing masked modeling methods typically reconstruct raw joint coordinates, emphasizing low-level detail and remaining sensitive to noise, while recent non-reconstruction variants predict learned latent features that improve semantics but capture little explicit motion structure. We propose **Path-JEPA**, a self-supervised predictive learning framework that adopts path signatures as the prediction target for skeleton sequences. Rather than predicting coordinates or abstract embeddings, Path-JEPA predicts latent representations of continuous-time, multi-scale geometric descriptors computed over joint, edge, and chain paths, capturing motion across multiple spatial and temporal scales. These targets encode displacement, signed area, and higher-order interactions, yielding a geometry-grounded representation of human motion that is naturally robust to temporal resampling and frame-rate variation. To make such targets effective within a JEPA framework, we introduce *signature-augmented masking*, which propagates joint-space masks to all dependent signature tokens, forcing the model to infer the missing motion geometry from broader anatomical and temporal context. Because signatures summarize motion over intervals rather than individual frames, they also yield greater computational efficiency on long sequences. Extensive experiments on NTU RGB+D 60, NTU RGB+D 120, and PKU-MMD show that Path-JEPA learns stronger representations than prior masked prediction methods, achieving state-of-the-art performance across diverse downstream tasks while exhibiting improved robustness to irregular sampling.



| Button | Points to |
| --- | --- |
| Paper | ECCV proceedings: `https://doi.org/10.1007/978-3-032-37258-1_7` (or a `paper.pdf` in the repo) |
| Video | https://www.youtube.com/watch?v=RNr8g3KlL54 |
| Poster | https://eccv.ecva.net/media/PosterPDFs/ECCV%202026/4270.png?t=1788326396.4086194 |
| PaperNotes | https://en.papernotes.org/ECCV2026/video_understanding/path-jepa_path_signature_based_predictive_learning_for_skeleton_action_recogniti/ |
| Code | **Coming soon** — label the button "Code (coming soon)" and leave it unlinked until the release; then point it to the GitHub repository |



The official ECCV entry is out: LNCS vol. 17054, pp. 110–128, DOI `10.1007/978-3-032-37258-1_7
