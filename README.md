# Data Science Exam
*by Felicia Heilgendorff and Martine Greve*

In this project we built text-based BERT, Naïve Bayes, LSTM and SVM models that classify stories either as remembered or imagined. We also built variable-based binary classification models that classify texts either as remembered or imagined based on external variables (not the story texts). Additionally, we performed topic modeling on our texts.

Data is saved in [hippoCorpusV2.csv](hippoCorpusV2.csv) and was taken from:

Sap, M., Horvitz, E., Choi, Y., Smith, N.A., & Pennebaker, J. (2020). Recollection versus Imagination: Exploring Human Memory and Cognition via Neural Language Models. Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, 1970-1978. https://doi.org/10.18653/v1/2020.acl-main.178

## Scripts

Topic modeling: [topicmodeling.ipynb](topicmodeling.ipynb) (including original category word clouds)

BERT: [BERT.ipynb](BERT.ipynb)

LSTM: [LSTM.ipynb](LSTM.ipynb)

Naive Bayes and SVM: [NaiveBayes_SVM.ipynb](NaiveBayes_SVM.ipynb)

Variable-based binary classification (logistic regression, ridge classifier, SGD classifier): [variablebased_binary.ipynb](variablebased_binary.ipynb) (including visualisations of data)
