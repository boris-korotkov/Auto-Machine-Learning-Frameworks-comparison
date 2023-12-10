# Auto Machine Learning Frameworks comparison

 I enjoyed my machine learning experience, but it was really boring to select the best machine learning algorithm and tune the hyperparameters. Luckily, people around the globe shared my feelings and invented automated machine learning frameworks. I decided to select a few of them and compare the efforts and results with the Machine Learning project I had in Data Science course at University of Toronto. 

   Out of variety of options, I selected [Auto-sklearn](https://automl.github.io/auto-sklearn/master/index.html), [Tree-based Pipeline Optimization Tool (TPOT)](http://epistasislab.github.io/tpot/), and [Fast and Lightweight AutoML (FLAML)](https://github.com/microsoft/FLAML). I used the default settings in all frameworks and left the data preparation at the same level as an in original machine learning exercise.

   The Jupyter Notebook: https://github.com/boris-korotkov/Auto-Machine-Learning-Frameworks-comparison/blob/main/AutoML_framework_comparison.ipynb

   I've got the super exciting result! The accuracy of Auto ML models was very close to the original super tuned machine learning project, but I spent minutes to write the code and train the model instead of many and many hours of work in the original project! I love automated machine learning!

   The best AutoML model out of three was TPOT one with R2 score equal to 0.9288 and the original top one was GradientBoostingRegressor with R2=0.9197.

   `Toolset: Python, Colab, Auto-sklearn, TPOT, FLAML`
