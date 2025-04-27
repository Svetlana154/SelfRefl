Original SQUAD 2.0 dataset was acquired from Kaggle: 

```
https://huggingface.co/datasets/rajpurkar/squad_v2
```

The resulting processed dataset is found in this directory. There are two variants: ```squad_2_with_few_shot_gpt2.parquet``` is the full validation split supplemented with few shot examples from the original training split, while ```squad_2_with_few_shot_gpt2_5000.parquet``` is a subset of the first 5000 examples from the first file.


The script that did the processing can be found under ``./script``.