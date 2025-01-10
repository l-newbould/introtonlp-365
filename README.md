# Introduction to NLP Course Notebooks

Welcome to the **Introduction to NLP** course repository! 

This repository contains Jupyter notebooks designed to help you learn the basics of Natural Language Processing through hands-on exercises.

The notebooks are designed to accompany the Introduction to NLP course which can be found here: 

https://learn.365datascience.com/courses/nlp

https://www.udemy.com/course/intro-to-natural-language-processing-in-python-for-ai/

## Installed Packages

These are the installed packages and versions used for this course. All were installed in a conda environment (see below for how I created this). 

python=3.11

```
nltk==3.9.1 
pandas==2.2.3 
matplotlib==3.10.0 
spacy==3.8.3 
textblob==0.18.0.post0 
vaderSentiment==3.3.2 
transformers==4.47.1 
scikit-learn==1.6.0 
gensim==4.3.3 
seaborn==0.13.2 
torch==2.5.1 
ipywidgets==8.1.5
```

## Updates

The world of AI is constantly evolving with new techniques and models emerging all the time. So, while we do our best to keep everything up to date, sometimes the code in this repo may get updated before the accompanying video lessons. To make sure you're getting the most out of this course, we recommend you always use the latest code here alongside the video lessons, while we work on updating the videos. 

## Conda Environment

Virtual environments are a great way to manage different packages for different projects. Creating a virtual environment for this section of the course allows you to ensure you can use the correct packages to follow along, without affecting any other packages you already have installed. 

```
conda create --name nlp_course_env python=3.11
conda activate nlp_course_env
pip install nltk==3.9.1 pandas==2.2.3 matplotlib==3.10.0 spacy==3.8.3 textblob==0.18.0.post0 vaderSentiment==3.3.2 transformers==4.47.1 scikit-learn==1.6.0 gensim==4.3.3 seaborn==0.13.2 torch==2.5.1 ipywidgets==8.1.5
python -m spacy download en_core_web_sm
pip install ipykernel jupyterlab notebook
python -m ipykernel install --user --name=nlp_course_env
```

Then when in the notebook, remember to check the kernel is set to "nlp_course_env". 


