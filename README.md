# Hybridization & Quantitative Comparison of Data-centric and Model-centric approaches

## Introduction
- This repository consists of the code for our Research Paper, titled "**Hybridization & Quantitative Comparison between Model-centric and Data-centric AI approaches**".
- We will primarily be using Kaggle for coding purposes, and we have uploaded a copy of the dataset on Kaggle for ease of access in our kernels, which can be accessed [here](https://www.kaggle.com/dataset/95840441821df30ede490fae5ba502b652d1457ca80f7b8d0f0c1212d9a260f7). Apart from containing the CIFAR-10 dataset in it's original form, this dataset also stores all the intermediate data files that are generated from one particular kernel as the output, and are used in another kernel as the input.
- We have also uploaded another dataset [here](https://www.kaggle.com/datasets/elemento/dcai-rw), which stores all the models. This is primarily being done to ensure reproducible results.

## Methodology
- We will primarily be creating a notebook for each of our data-centric methods, and then evaluating those methods on the same CIFAR-10 dataset in terms of **log-loss** and **accuracy**.
- Similarly, we will be creating a notebook for each of our model-centric methods, and then evaluating those methods on the same CIFAR-10 dataset in terms of **log-loss** and **accuracy**.
- In order to compare the methods, we have performed the **same hyper-parameter tuning** for all our models/methods including the baseline model. The parameter that we have tuned is the **#epochs**, from **[10, 20, 30, 40, 50]**, and we have simply selected the setting (**#epochs**) with the largest accuracy on the test dataset.

## File Descriptions
- `exp_tra.ipynb` -- This `.ipynb` notebook covers the basic code of exploring the provided dataset files, and transforming them into the required `.csv` format. It also includes the code for unbalancing the dataset, and reserving some portion as the unlabelled dataset.
- `baseline_model.ipynb` - This file stores the code of the Baseline Model. It's a simple CNN model with considerable hyperparameter-tuning, and has an **accuracy of 0.7822**, a **weighted f1-score of 0.7805** and a **log-loss of 0.7801** on the test dataset.


## Authors
- Dr. Surya Prakash
- Vishesh Mittal
- Mitisha Agarwal