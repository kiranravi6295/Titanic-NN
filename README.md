
# Kaggle submission for Titanic survival prediction using basic Deep Learning

Kaggle is the Go-To website for anyone who is interested in data science with its wide range of datasets. You can access the titanic challenge [here](https://www.kaggle.com/c/titanic).

## Installation Guide

You need to have an installation of Anaconda. Please download and follow the install steps [here](https://www.anaconda.com/distribution/).

After install, follow below steps :
- Clone/ Download the repo. Open Anaconda Prompt and navigate to the folder location.
- Create a new python 3 workspace.
```
conda create --name your_env_name python=3 -y
```
- Activate the newly created workspace. After this you should be able to see the workspace name instead of `(base)`
```
activate your_env_name
```
- Run the following to install prerequisites
```
conda install -c conda-forge matplotlib missingno seaborn numpy pandas -y
conda install -c pytorch pytorch torchvision -y
```

## Getting the result

- Open the folder containing the notebook in anaconda Prompt and activate the python 3 environment created above.
- Run the Jupyter Notebook
```
jupyter notebook
```
- Open Titanic NN.ipynb and Run all.
- Find the Titanic_NN_submission.csv file with predictions.

## License

Feel free to do anything with it.
