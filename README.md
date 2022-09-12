# Paraphrase detection system and dataset for the Spanish language

## Considerations

The provided notebooks are designed to be executed on the Google Colab platform. Despite that, feel free to use the code however you might need, but keep in mind that, downloading this repository and uploading it to google drive, will significantly ease the experience.

## Objectives

- Spanish dataset for the paraphrase detection task
- Paraphrase detection systems:
  - Cosine distance
  - SVM
    - Tf-Idf, spaCY
    - RandomOverSampler, SMOTE
  - BERT: finetuned for the English MRPC dataset (we use transfer learning between languages)
