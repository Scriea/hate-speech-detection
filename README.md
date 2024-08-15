# Hate_speech_classifier [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14eAHQBUhkvTIzS04CDPvUWNto5fvTl5F?usp=sharing)

This project involves training a language model for hate speech detection using the BERT LM.

- **Model** : [distilbert-base-uncased](https://huggingface.co/distilbert/distilbert-base-uncased)
- **Epochs : 4**
- **Dataset :** [Hate-Speech UC Berkeley
  ](https://huggingface.co/datasets/ucberkeley-dlab/measuring-hate-speech)
  
  The dataset contains 7 target attributes : *race*, r*eligion, origin, gender, sexuality, age, disability*

#### Packages:

```
numpy
torch
datasets
tqdm
evaluate
transformers==4.28.0
```

Task: The task is to classify text into multiple hate speech categories. The script utilizes multi-label classification techniques, where a single input text can belong to multiple hate speech categories simultaneously.
