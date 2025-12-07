## Materials for "How to Win a Data Science Competition: Learn from Top Kagglers" course

This repository contains programming assignments notebooks for the [course](https://www.coursera.org/learn/competitive-data-science/home/welcome) about competitive data science.

# Quiz Solutions provided by other users

[link 1](https://static1.squarespace.com/static/5a4c161cfe54ef45b17aa18e/t/5ab4013b88251b7b684c6025/1521746286132/week2-part2.pdf)
[link 2](https://necromuralist.github.io/kaggle-competitions/)

# Enviroment Setup

Install miniforge <https://github.com/conda-forge/miniforge>

Create mamba env

```base
mamba create -n kaggle \
    python numpy scipy pandas matplotlib catboost datasets transformers debugpy duckdb graphviz lightgbm nltk optuna peft pillow \
    plotly polars pyarrow pydantic pytest timm tqdm umap-learn wandb einops seaborn xgboost scikit-learn pytorch torchvision \
    ipykernel nbformat \
    -c conda-forge
```
