# SelfRefl
Code and data used to implement the experiments for the paper _"When One Size Doesn’t Fit All: A Study on Intrinsic Iterative Self-Correction in LLMs for Hallucination Control"_ by S. Esina and D. Inkpen. Please find the full paper at: [Link to be confirmed]

This repository includes:
1. The initial scripts for loading and processing the datasets (SQUAD 2.0 and TruthfulQA)
2. The `.parquet` files of the processed datasets used in the self-correction experiments
3. The iteration-0 scripts for Qwen2.5, Llama3.2 and Gemma2 for generating the initial response in the QA task
4. The iteration-n scripts for Qwen2.5, Llama3.2 and Gemma2 for running self-correction on the initial response

> Please note that all the scripts presented in this repository may have been modified to avoid leakage of personal API keys and filepaths. Thus, in order to replicate the results obtained in the paper, the scripts may need to be supplemented with the missing information.

## Environment
These scripts were executed in Kaggle Notebooks, with the GPU accelerator set to GPU T4 x2.
