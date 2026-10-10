# GAN for PSHA

### Title

Application of a Generative Adversarial Network Model to enhance the performance of complex Probabilistic Seismic Model

### Authors

Martin Nguyen, Jian Di

## Overview

Probabilistic Seismic Hazard Analysis (PSHA) is used in Open Quake Engine to produce tabular data containing earthquake information. However, the PSHA procedure is extremely complex and computationally time-consuming. Hence, this project aims to apply a machine learning model to speed up the procedure. Accordingly, the Conditional Tabular Generative Adversarial Network (CTGAN) model was selected and tuned to learn the underlying earthquake features. It used a small sample (10% ~ 20%) of the tabular data to generate the synthetic dataset for reducing the complexity and the computation time. In this project, the performance of the CTGAN was assessed by Logistic Detection, Cosine Similarity, Pearson's and Spearman's Correlation, and Mapping.

<img width = "100%" src="https://github.com/Martin20494/GAN_for_PSHA/blob/main/comparison.png">

The first column presents two results from PSHA, and the second column presents two results from the CTGAN. The two columns are highly similar to each other which means that the CTGAN can learn the underlying features of the earthquake information and there is potential that CTGAN can be used to speed up the PSHA procedure.

## Description

There are 8 files in the folder:
- Poster (Both ppt and pdf files)
- Presentation (ppt file)
- Report (Both word and pdf files)
- The script (3 files)

As to the script files, there are 3 types:
- File 1: The selected sub-dataset
- File 2: The selected sub-dataset with a trial solution for PGA patterns only (not for PGA value)
- File 3: The full dataset (tried with 10 epochs. Notice: for 10 epochs, the script was run in a week without the support from GPU or TPU and required the RAM of about 60 GB. Please make sure you can satisfy the requirements about the RAM memory and have the support from GPU or TPU to let the codes run within your given time)

These script files could be run on Google Colab or Jupyter Notebook (with some adjustment. Please let me know if it could not work)

The link for the datasets: https://www.dropbox.com/sh/vmst2jyz61x9mzn/AAD7KNKBJqqHeMqG480cKjCba?dl=0

## Contacts

Github author: Martin Nguyen martinnguyen20494@gmail.com
