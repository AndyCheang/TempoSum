# **TempoSum: Evaluating the Temporal Generalization of Abstractive Summarization**

This repository contains data for our paper [TempoSum: Evaluating the Temporal Generalization of Abstractive Summarization](https://arxiv.org/abs/2305.01951)

## Getting the data

### Download the datasets from Huggingface Datasets Library 

Run the following commands to to load the datasets from Huggingface Datasets Library.

```python
import datasets

# BBC in-distribution test set
dataset = datasets.load_dataset('chiseng-cheang/TempoSum', 'BBC_in-distribution')

# BBC future test set
dataset = datasets.load_dataset('chiseng-cheang/TempoSum', 'BBC_future')

# CNN in-distribution test set
dataset = datasets.load_dataset('chiseng-cheang/TempoSum', 'CNN_in-distribution')

# CNN future test set
dataset = datasets.load_dataset('chiseng-cheang/TempoSum', 'CNN_future')
```

### Manual Download

All datasets are also available at: https://drive.google.com/drive/folders/1BdeTFqoea8GD240h78PgXBO68e53ea9E?usp=sharing
