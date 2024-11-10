# SC4002 Natural Language Processing G39 Project

## **Members**
1. Isaiah Loh Kai En (U2140496L)
2. Li Zihan (U2121598G)
3. Lye En Lih (U2121387B)
4. Ong Yi Xin Kelly (U2040271D)
5. Wang Shang An Davis (U2121998F)
6. Zhang Jing Wen (U2121853G)

## **Project Overview**
In this assignment, you will build a general classification system built on top of the existing pretrained
word embeddings, e.g., word2vec or Glove. The system is used to perform sentence classification
tasks, specifically Sentiment Classification in this project, which assigns a sentiment label to
each sentence. The objective of this exercise is for you to be familiar with typical NLP applications
of word embeddings and typical deep learning models for sentence classification tasks. You will
also practice how to train effective classifiers from pretrained word embeddings and evaluate the
performances.


## **Setup Instructions**

### **1. Prerequisites**
Ensure you have the following installed on your system:
- Python 3.9 or higher
- Conda or Miniconda for virtual environment management

--- 

### **2. Create a Virtual Environment**
Use Conda or Miniconda to create and activate a virtual environment (downgrade or upgrade Python Version when necessary):

**For Conda**
```bash
conda create --name nlp_project_G39 python=3.12
conda activate nlp_project_G39
```
---

### **3. Install Required Libraries**
Install all required libraries using the provided requirements.txt file:
```bash
pip install -r requirements.txt
```
---
### **4. Open Jupyter Notebook**
Open Jupyter Notebook in your current virtual environment
```bash
jupyter notebook
```
---
### **5. Running of Codes**
Ensure that the notebook ```SC4002_G39_Part1.ipynb``` is the first notebook being run in order to install and save the pre-trained gloVe and Word2Vec models.

Separately, install the following models using the embedded links
### 1. [```wiki.en.vec```](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.en.vec)
### 2. [```cc.en.300.vec```](https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.en.300.vec.gz)

After which, run the individual notebooks from Part 2 to Part 3.5 as necessary to get the outputs for the models trained. Take note that file directories will need to be updated manually.

---
