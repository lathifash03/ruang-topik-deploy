# fp-textmining

# Ruang Topik: Topic Modeling on Indonesian News

Topic modeling pipeline for Indonesian-language news articles, with a small app to explore the discovered topics. Built as a text mining course project; this repository is my own deployment of the work.

## What is in this repository

| Path | Contents |
|---|---|
| `03_topic_modeling_s1.ipynb`, `04_topic_modelling_s2.ipynb`, `05_topic_modeling_s3.ipynb` | Three experiment scenarios for topic modeling |
| `03_topic.ipynb` | Exploratory topic modeling notebook |
| `hasil_optuna_hyperparameter.csv` | Hyperparameter search results (Optuna) |
| `app/` | Application for exploring the topics |
| `code/` | Supporting code |
| `output/` | Generated outputs |

## Method

1. Collect and preprocess Indonesian news text (cleaning, tokenization).
2. Build document representations [describe: e.g. TF-IDF / BERT embeddings].
3. Fit topic models under three scenarios (S1 to S3) and tune hyperparameters with Optuna.
4. Compare scenarios with [metric you used, e.g. topic coherence] and inspect topics.

## Results

[Add the main result with its number, e.g. the best scenario, its metric value, and the number of topics.]

## Data

The news dataset is not included in this repository for copyright reasons. [State the source of the articles and how to obtain them.]

## Run the app locally

```bash
git clone https://github.com/lathifash03/ruang-topik-deploy.git
cd ruang-topik-deploy
pip install -r requirements.txt
[command to start the app, e.g. streamlit run app/app.py]
```

## Limitations

[One or two honest limitations: dataset size or period, evaluation metric, language coverage.]

## Author

Lathifah Sahda. Portfolio: https://lathifash03.github.io
