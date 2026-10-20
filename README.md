# Skincare-Product-Recommendation-System
A machine learning project that recommends skincare products from natural-language descriptions of skin type and concerns (e.g., “dry skin with redness”). It compares a rule-based baseline (pre-trained Sentence-BERT + skin-type matching) with a neural network trained from scratch in PyTorch on frozen Sentence-BERT embeddings. Trained on synthetic queries and rule-derived labels; see the report for limitations.

Try the demo here: https://huggingface.co/spaces/keanjg28/skincare-recommendation-ml-system

**Training Data**

The full training files used for this project are available on Zenodo due to size limits on GitHub:

🔗 https://zenodo.org/records/17887635

These files are optional for running the notebook. You do NOT need to download them to successfully run the project.

All that is required is the cosmetic_p.csv file placed in your working directory. When you run the notebook consecutively, all additional training files and processed datasets are automatically generated during execution.

**Evaluation**

For evaluation, the files located in data/model can be used immediately. These can be uploaded directly through the notebook’s upload interface to run the evaluation notebook without re-training the models.

**Project Report**

A detailed technical report describing the model architecture, training process,
feature engineering, and evaluation methodology is available here:

[Project Report](https://drive.google.com/file/d/1w1VXthymDg8gyTKfRzq3PwE3ch4MDUMG/view?usp=sharing)
