# Quora-Question-Pairs
Machine Learning Model which predicts whether the provided pairs of questions have a similar meaning or not

**Breif Description :**


![image](https://user-images.githubusercontent.com/62200958/125176380-8eda3d80-e1f0-11eb-8ae9-03bd9776fa0a.png)


Quora is a platform for learning and sharing information. It's a place where we can ask questions and get responses from people who have unique perspectives and answers.With over 100 million monthly users on Quora, it's no wonder that many individuals ask similar questions. Many questions with the same objective can lead people spending more time looking for the best solution to their Query, as well as writers feeling obligated to respond to multiple variations of the same question. so,this machine learning model can find similar questions and sloves our query with no time.

The ground truth is the set of labels that have been supplied by human experts. The ground truth labels are inherently subjective, as the true meaning of sentences can never be known with certainty. Human labeling is also a 'noisy' process, and reasonable people will disagree. As a result, the ground truth labels on this dataset should be taken to be 'informed' but not 100% accurate, and may include incorrect labeling. We believe the labels, on the whole, to represent a reasonable consensus, but this may often not be true on a case by case basis for individual items in the dataset.

All of the questions in the training set are genuine examples from Quora.The test set is computer-generated question pairs by Kaggle.

## Project Tree Structure
```
📦 Quora-Question-Pairs
├── README.md
├── data
     ├── before_f_e.rar
     ├── for_A_f_e.rar
     ├── train.csv.zip
├── html files
     ├── afterbasicexcration.html
     ├── nlpfeatures.html
     ├── output_min.html
├── ipynb files
     ├── Advance_Feature__Engineering.ipynb
     ├── Feature_engineering.ipynb
     ├── data_explanation.ipynb
     ├── word2vec.ipynb
```
## Tools Used
- Programming language : Python

- Visualization : Matplotlib,Seaborn and pandas profiling

- Version control system : GitHub

## References
 

[problem statement](https://www.kaggle.com/c/quora-question-pairs/overview)

[Data](https://www.kaggle.com/c/quora-question-pairs/data)

[Blog](https://towardsdatascience.com/identifying-duplicate-questions-on-quora-top-12-on-kaggle-4c1cf93f1c30)

[fuzzywuzzy](https://www.analyticsvidhya.com/blog/2021/06/fuzzywuzzy-python-library-interesting-tool-for-nlp-and-text-analytics/)






