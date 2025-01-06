# Introduction to NLP Course Notebooks

Welcome to the **Introduction to NLP** course repository! 

<<<<<<< HEAD
🎓 This repository contains Jupyter notebooks designed to help you learn the basics of Natural Language Processing through hands-on examples and exercises.

## Installed Packages

These are the installed packages and versions used for this course. All were installed on a virtual environment (please see the section below to learn more about virtual environments and set up your own) using pip.

nltk==3.9.1
pandas==2.2.3
matplotlib==3.10.0
spacy==3.8.3
en_core_web_sm==3.8.0
textblob==0.18.0.post0
vaderSentiment=3.3.2
transformers==4.47.1
torch==2.5.1+cu118
scikit-learn==1.6.0
gensim==4.3.3
seaborn==0.13.2

To install a package, go to your terminal and run `pip install <package_name>==<version>`.

## Setting up a Virtual Environment

Virtual environments are a great way to manage different packages for different projects. Creating a virtual environment for this section of the course allows you to ensure you can use the correct packages to follow along, without affecting any other packages you already have installed. 

You'll also want to set up a Jupyter kernel in your virtual environment so you can run the Jupyter notebooks. 

Doing this is easy, just follow along below. 

Install virtualenv

```
pip install virtualenv
```

Create your virtual environment in a directory of your choice

```
virtualenv yourenvname # replace yourenvname with any name you like
``` 

Activate the virtual environment 

```
# on mac or linux
source myenv/bin/activate

# on windows
myenv\Scripts\activate
```

Install jupyter

```
pip install jupyter
pip install ipython
pip install ipykernel
```

```
ipython kernel install --user --name=myenv
python -m ipykernel install --user --name=myenv
```

Install the bash kernel

```
pip install bash_kernel
python -m bash_kernel.install
```

Start your jupyter notebook

```
jupyter notebook
```

Then when in the notebook, remember to change the kernel to "myenv". 

Make sure to then install any packages within this virtual environment. 

=======
🎓 This repository contains Jupyter notebooks designed to help you learn the basics of Natural Language Processing (NLP) through hands-on examples and exercises.
>>>>>>> f5f037656f1bd01188f70546802a1a48de6bf00c

