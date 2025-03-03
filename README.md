# Efficient-CNN-BiLSTM-for-Network-IDS

Code for Paper : Efficient-CNN-BiLSTM-for-Network-IDS

Paper is available here: https://dl.acm.org/doi/10.1145/3430199.3430224

# For people looking to reproduce the results:
You can use below public Kaggle notebook in order to reproduce the results. Notebooks below are for multiclass classification, you can modify them for binary!

1. UNSW Multiclass: [https://www.kaggle.com/razor08/unsw-categorical-final](https://www.kaggle.com/razor08/unsw-categorical-final-separate-test-set)
2. NSL KDD Multiclass: [https://www.kaggle.com/razor08/nsl-kdd-categorical ](https://www.kaggle.com/razor08/nsl-kdd-categorical )

[Update: 10/25/2022]
There were a few citations to our paper that reflected that we did not use a separate test set to report our validation score, the notebook for UNSW above has been updated with one that includes separate test set. Apparently, we shared an earlier version of Notebook where we were optimising for hyperparameters. Hope this helps clear up the confusion.

# Update 03/03/2025

In this fork I updated all python dependencies to the latest versions and fixed the code to work with the latest versions of the libraries. Furthermore, I added [juv](https://github.com/manzt/juv) to notebooks contain their requirements and can be run with:

```bash
uvx juv run NSL_KDD_Final.ipynb
```

Ensure [uv](https://github.com/astral-sh/uv) is installed on your system.
