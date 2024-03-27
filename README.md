# Red-Teaming Segment Anything Model
Source code for the paper "Red-Teaming Segment Anything Model" accepted at CVPR 2024 4th Workshop of Adversarial Machine Learning on Computer Vision: Robustness of Foundation Models.

### Repository contents
Repository contains 3 notebooks:
- sam_style_transfer.ipynb - experiments to assess the quality of generated masks under different weather conditions.
- sam_facial_recognition.ipynb - experiments to check whether LangSAM (version of Segment Anything with text prompts input) can unintentionally classify celebrities when prompted with a full name.
- destroy_lang_sam.ipynb - experiments with adversarial attacks

### Used code repositories
Our code uses parts of these repositories:
- SAM: https://github.com/facebookresearch/segment-anything
- LangSAM: https://github.com/luca-medeiros/lang-segment-anything
- Multiweather city dataset: https://github.com/vnmusat/multi-weather-city

### Ethical principals
Our research adheres to ethical principles and we expect all users to employ it responsibly
and only for noble intentions.
