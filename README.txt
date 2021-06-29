Two .ipynb notebooks are included for this project.

1. Cooking with Leftovers
2. Cooking with Leftovers Neural Network

Data used in this project can be found from this google drive link:
https://drive.google.com/drive/folders/1D5CGHJ_7g4Vj7D6LRcVWDack2P8bVpg2?usp=sharing

Please refer to 'Cooking With Leftovers.ipynb' first, for data cleaning, feature engineering, and models.
Afterwards, refer to 'Cooking with Leftovers Neural Network.ipynb' for deep learning models.

In order to run the deep learning models, a new environment must be created.
The following steps will install the environment used for these models.

1. conda create -n deeplearning python=3.8
2. conda activate deeplearning
3. conda install numpy=1.19.2 pandas matplotlib jupyter jupyterlab pydot pillow seaborn
4. pip install --upgrade pip
5. pip install tensorflow==2.2
6. conda install scikit-learn=0.24.1 nltk
7. conda install -c conda-forge gensim=3.8.3
8. conda install -c pytorch pytorch=1.4 torchvision=0.5.0
9. conda install -c conda-forge tqdm

Optional. Creating a Jupyter kernel for this environment (needed if you don't have nb_conda_kernels installed in your base environment):

ipython kernel install --name "deeplearning" --user