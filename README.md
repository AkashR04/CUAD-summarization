# Contract Analyzer and Summarizer

This repository contains an analysis of various summarization models for contract summarization. The goal is to evaluate the performance and effectiveness of different models in generating concise and informative summaries from longer documents.

## Table of Contents

- [Introduction](#introduction)
- [Models](#models)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Contract summarization is the task of condensing a longer document into a shorter summary while preserving the key information and main ideas. This project aims to analyze and compare the performance of different summarization models using popular evaluation metrics. By examining the strengths and weaknesses of each model, we can gain insights into their capabilities and identify areas for improvement.

## Models

The following summarization models are included in this analysis which have been imported from huggingface:

1. Model A: facebook/bart-large
2. Model B: google/pegasus-large
3. Model C: t5-base

Feel free to add more models to the list as needed.

## Dataset

We utilize a diverse dataset of documents for training, validation, and testing the summarization models. The CUAD dataset, version 1, is a collection of over 13,000 annotations from 510 commercial legal contracts. These contracts have been carefully labeled to identify 41 categories of significant clauses that are important for lawyers during contract review in corporate transactions.

CUAD is a curated dataset maintained by The Atticus Project, Inc. It serves as a valuable resource for NLP research and development in the field of legal contract review. For in-depth analysis of CUAD, please refer to the following link: https://arxiv.org/abs/2103.06268. Additionally, the code required to replicate the results and access the trained model can be found at: https://github.com/TheAtticusProject/cuad.


## Results

The results of the analysis, including evaluation metrics and comparison of the summarization models, can be found in [[link to the results file or notebook](https://colab.research.google.com/github/AkashR04/CUAD-summarization/blob/main/Summarization_Demo_Smaller_Evaluation.ipynb)].

## Contributing

Contributions to this project are welcome! If you would like to add more models, improve the analysis, or suggest enhancements, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes and commit them: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and analysis as per the terms of this license.

Please note that the dataset and specific models used in this analysis might have their own licenses and restrictions. Refer to the respective sources for more information.

Happy summarizing!
