# Natural Images Processing and Classification


1. Dataset:
- This dataset contains 6000+ images from 8 distinct classes: airplane, car, cat, dog, flower, fruit, motorbike, and person
2. Goal:
- The project aims to build a classification model to best predict a class label among all the eight possibilities for the images in the test set
3. Result:
- Trained a model/pipeline that achieves 0.77 classification accuracy on the test set
- Seleted model: StandardScaler() --> PCA(n_components=50) --> StandardScaler() --> SVC(kernel='rbf', gamma='scale', C=10)
4. Implementation:
- Built machine learning pipelines to predict natural images among eight distinct classes, with models such as k-Nearest
Neighbors, Random Forests, Support Vector Machines, and PCA, achieving 0.77 accuracy via selected models
- Evaluated generalization performance with cross validation and metrics such as confusion matrix and f1-score
- Improved models with grid search on hyperparameters and preprocessing steps such as feature extraction
5. Reference:
- https://www.kaggle.com/prasunroy/natural-images
- An Introduction to Machine Learning with Python by Andreas C. Müller and Sarah Guido (O’Reilly). Copyright 2017 Sarah Guido and Andreas Müller, 978-1-449-36941-5
