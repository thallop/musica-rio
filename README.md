This repository contains the code associated with the scientific publication:  
**"MUSICA: A Multi-Source Informal Settlement Classification Approach Combining Remote Sensing Foundation Models and Expert Knowledge"**

## 📂 Structure
- `deep_feature_extraction.ipynb` → Satellite images preprocessing and tiling, and deep feature extraction using [https://github.com/antofuller/CROMA](https://github.com/antofuller/CROMA) or [https://huggingface.co/BIFOLD-BigEarthNetv2-0/resnet50-all-v0.2.0](https://huggingface.co/BIFOLD-BigEarthNetv2-0/resnet50-all-v0.2.0)
- `modeling_and_evaluation.ipynb` → Training and evaluation of classification models (single-view baselines, early fusion baseline, intermediate fusion baseline, MUSICA late fusion approach)

Expert feature engineering is handled in a separate repository:  
[https://github.com/thallop/BALISE](https://github.com/thallop/BALISE)

## 📄 Citation
If you use this code or build upon this work, please cite:

```bibtex
@article{hallopeau2025musica,
  title   = {MUSICA: A Multi-Source Informal Settlement Classification Approach Combining Remote Sensing Foundation Models and Expert Knowledge},
  author  = {Hallopeau, Thomas and Guérin, Joris and Vanderlei, Matos and Gurgel, Helen and Demagistri, Laurent},
  year    = {2026},
  journal = {Neurocomputing}
}
