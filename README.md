# mtsmlcup
A 17th place solution for MTS ML CUP competition using [pytorch-lifestream](https://github.com/dllllb/pytorch-lifestream) or ptls


## Install pytroch-lifetsream

```sh
pip install pytorch-lifestream
```

## List of notebooks

- Prepare raw clicksteream for ptls format [notebook](notebooks/prep_transactions.ipynb)
- Alternative prepare raw clicksteream for ptls format and split host to domain levels [notebook](notebooks/prep_transactions_split.ipynb)
- Create some handmade features including pivots and aggregates [notebook](notebooks/prep_transactions_split.ipynb)
- ALS based user factors baseline [notebook](notebooks/context_baseline_public.ipynb) 
- Unsupervised pretrain COLES embeddings [notebook](notebooks/coles_pretrain.ipynb)
- Unsupervised pretrain COLES embeddings with host split [notebook](notebooks/coles_pretrain_split.ipynb)
- Unsupervised pretrain COLES embeddings with additional augmenation: time shuffle and dropout of sequence items [notebook](notebooks/coles_pretrain_shuffle.ipynb)
- Supervised pretrain COLES embeddings [notebook](notebooks/coles_supervised.ipynb)
- Finetune COLES embeddings to targed [notebook](notebooks/coles_finetune.ipynb)
- Finetune COLES embeddings to targed with split hosts [notebook](notebooks/coles_finetune_split.ipynb)
- Unsupervised pretrain MLM embeddings [notebook](notebooks/mlm_pretrain.ipynb)
- Unsupervised pretrain tabformer embeddings [notebook](notebooks/tabformer.ipynb)
- Concatenate all embeddings and features then solve downstream task [notebook](notebooks/downstream.ipynb)
- Learn separate classifiers for each features and combine to solve downstream task [notebook](notebooks/blending.ipynb)
