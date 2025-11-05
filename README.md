# [EMNLP 2025] Data-Descriptions-from-Large-Language-Models-with-Influence-Estimation, EMNLP 2025

This repository is official for "[Data-Descriptions-from-Large-Language-Models-with-Influence-Estimation]([[https://arxiv.org/abs/2310.19264](https://aclanthology.org/2025.emnlp-main.1717/)](https://aclanthology.org/2025.emnlp-main.1717/))", EMNLP 2025.

## Abstract

Deep learning models have been successful in many areas but understanding their behaviors still remains a black-box. Most prior explainable AI (XAI) approaches have focused on interpreting and explaining how models make predictions. In contrast, we would like to understand how data can be explained with deep learning model training and propose a novel approach to understand the data via one of the most common media - language - so that humans can easily understand. Our approach proposes a pipeline to generate textual descriptions that can explain the data with large language models by incorporating external knowledge bases. However, generated data descriptions may still include irrelevant information, so we introduce to exploit influence estimation to choose the most informative textual descriptions, along with the CLIP score. Furthermore, based on the phenomenon of cross-modal transferability, we propose a novel benchmark task named ~\emph{cross-modal transfer classification} to examine the effectiveness of our textual descriptions.  In the experiment of zero-shot setting, we show that our textual descriptions are more effective than other baseline descriptions, and furthermore, we successfully boost the performance of the model trained only on images across all nine image classification datasets. These results are further supported by evaluation using GPT-4o. Through our approach, we may gain insights into the inherent interpretability of the decision-making process of the model.

## Overall

![overall](figure/approach.png)


## How to train
Codes will be released soon!


## Citation
To be written
