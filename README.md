# semi-supervised learning on the covid 19 tweets dataset
- In this project I'm showing the importance of semi-supervised learning by training different semi-supervised machine learning models on the covid 19 tweets dataset with only 20% of the dataset is labeled and comparing these models to supervised machine learning models trained only on the 20% labeled part of the dataset.
- The technologies I used on this dataset are:
    - [SimCSE embeddings model](https://github.com/princeton-nlp/SimCSE) 
    - [scikit-learn semi-supervised machine learning models](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.semi_supervised)
    - [scikit-learn linear machine learning models](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.linear_model)
## Table of contents
1. Importing libraries.
2. Importing dataset.
3. data cleaning.
4. Creating the embeddings model and transforming the data.
5. Splitting the dataset.
    1. Spliting into training data and test data.
    2. Creating unlabeled data.
6. creating the machine learning models.
7. Evaluating the models.
    1. Label Propagation semi-supervised Model.
    2. Label Spreading semi-supervised Model.
    3. SGD supervised Model.

## How to install and run the project
- install the [SimCSE](https://github.com/princeton-nlp/SimCSE) library by following the [instructions](https://github.com/princeton-nlp/SimCSE/wiki/Installation) in the official page of the library.

## Credits
- I have created this project using :
    - [Self-supervised Semi-supervised Learning for Data Labeling and Quality Evaluation](https://arxiv.org/abs/2111.10932) research paper.
    - [SimCSE: Simple Contrastive Learning of Sentence Embeddings](https://arxiv.org/abs/2104.08821) research paper.
    - [SimCSE](https://github.com/princeton-nlp/SimCSE) library.
- I just want to show my appreciation to the teams worked on the research papers and the library for their great effort.

