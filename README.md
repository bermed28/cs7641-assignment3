# CS 7641 - Assignment 3: Unsupervised Learning & Dimensionality Reduction

This repository contains the experiments made to analyze and complete assignment 3 of the CS7641 - Machine Learning 
course from the Georgia Institute of Technology.

The main purpose of this assignment is to analyze 2 clustering algorithms:
* K-Means
* Expectation Maximization

3 linear dimensionality reduction techniques:
* Principal Components Analysis (PCA)
* Independent Components Analysis (ICA)
* Randomized Projections

and 1 non-linear manifold algorithm:
* t-Distributed Stochastic Neighbor Embeddings (t-SNE)

The goal is to see how we can use clustering & dimensionality reduction to do unsupervised learning tasks, as well as supervised learning tasks like neural network training.

We use the `scikit-learn` module to execute these experiments.

----

### Setup Virtual Environment

In the root directory of the project, do one of the following two

#### Conda

```shell
$ conda create --name myenv python=3.8
$ conda activate myenv
$ pip install -r requirements.txt
```

#### PipEnv

```shell
$ python -m venv /venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

### Run Scripts

Open up `clustering_dim_reduction.ipynb` in VS Code (or your preferred editor/jupyter server), select your virtual environment (in this example `myenv`) as your kernel and run the code cells one by one.

----

## Note: If you are a GT Student taking CS7641 **_DO NOT_** proceed looking at this repository in order to not violate the GT Academic Honor Code