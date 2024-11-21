# **NLP Task**

This project involves solving two NLP tasks: calculating **word similarity** and **sentence similarity**. The tasks are implemented using custom approaches and pretrained models, and the details are as follows:

---

## **Task 1: Word Similarity**

### **File**: `cbow.ipynb`

### **Objective**:  
Calculate word similarity without relying on pretrained models like Word2Vec or GloVe, and then compare it with the performance of pretrained models.

### **Approaches**:
1. **Custom Approach**:
   - Used the **Continuous Bag of Words (CBOW)** model.
   - This model is implemented from scratch without any pretrained embeddings.
   - A detailed explanation of the CBOW approach and the training process will be included in the report.

2. **Pretrained Models**:
   - Implemented word similarity using:
     - **Word2Vec** embeddings.
     - **GloVe** embeddings.
   - These pretrained models are used to showcase the difference in performance compared to the custom CBOW model.

---

## **Task 2: Sentence Similarity**

### **File**: `sentence_similarity_2.ipynb`

### **Objective**:  
Calculate sentence similarity using various methods and models.

### **Approaches**:
1. **Average Word Embeddings**:
   - Sentence embeddings are computed by averaging the word embeddings of all words in the sentence.
   - This method produced weak results, indicating its limitations.

2. **Doc2Vec Model**:
   - Used the **Doc2Vec** model to compute sentence or document embeddings.
   - Doc2Vec is trained to find robust embeddings for sentences, leading to improved similarity calculations.

---
