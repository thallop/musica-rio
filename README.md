This repository contains the code associated with the scientific publication:  
**"MUSICA: A Multi-Source Informal Settlement Classification Approach Combining Deep Learning and Handcrafted Spatial Features"**

## 📂 Structure
- `deep_feature_extraction.ipynb` → Satellite images preprocessing and tiling, and deep feature extraction using [https://github.com/antofuller/CROMA](https://github.com/antofuller/CROMA)
- `modeling_and_evaluation.ipynb` → Training and evaluation of classification models (single-view baselines, early fusion baseline, MUSICA late fusion approach)

Handcrafted feature engineering is handled in a separate repository:  
[https://github.com/thallop/BALISE](https://github.com/thallop/BALISE)

## 📄 Citation
If you use this code or build upon this work, please cite:

```bibtex
@article{hallopeau2025musica,
  title   = {MUSICA: A Multi-Source Informal Settlement Classification Approach Combining Deep Learning and Handcrafted Spatial Features},
  author  = {Hallopeau, Thomas and Guérin, Joris and others},
  year    = {2025},
  journal = {To appear}
}
