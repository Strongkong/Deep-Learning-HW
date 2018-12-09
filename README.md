# Deep-Learning-HW
## ClickStarter Team
Homework for Deep Learning 2018, BME

Finished milestone: Final milestone.

### Instructions to run the jupyter notebooks

We separated the whole project into four distinct notebooks. We created [another GitHub repository](https://github.com/Strongkong/cleaned_kickstarted_dataset) to store and share files between them, so you can run them separately in any order.

1. [Preparation of data](ks_preprocessing.ipynb): merging datasets, data transformations, feature engineering, data cleaning. The result is the dataset used to train the model.
2. [Data visualization](ks_visualization.ipynb): visualizations of the dataset to help understand the data more in details.
3. [Model optimization and training](ks_training.ipynb): optimizing the MLP NN parameters with Talos, analyzing the result and training the model. The output is the network's weights. We evaluated the models right after the training.

The uploaded jupyter notebooks have been run on Google Colab with the following installed packages:
* scikit-learn-0.20.1
* numpy-1.14.6
* pandas-0.22.0
* langdetect-1.0.7
* Pattern-3.6
* nltk-3.2.5
* matplotlib-2.1.2
* keras-2.2.4
* tensorflow-1.12.0
* talos-0.4.3

If they are not installed then they will be on the fly with pip commands in the notebooks. To reproduce the demonstration you only have to run the notebooks one after another.
