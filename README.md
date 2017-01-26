# Predicting Client Situation
Artificial Intelligence Beginner: Introduction to Machine Learning! Machine Learning system to predict client situation if he is "happy", "sad", "upset". In this project, you can predict if a client bought inside a website

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [Scipy](https://scipy.org/install.html)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

### Code

Template code is provided in the `sistuacao_do_cliente.py` and `situacao_do_cliente_kfold.py` (using k-fold cross-validation) file. You will also be required to use the `situacao_do_cliente.csv` dataset file to complete your work. 

### Data

The buscas dataset consists of 226 data points, with each datapoint having 4 features.

### Features

1. `recencia`: Last loggin (days)  
2. `frequencia`: Frequency total
3. `semanas_de_inscricao`: Total weeks registration
4. `situacao`: Identify if client is sad, happy, upset

**Target Variable**

`situacao`: Identify if client situation
