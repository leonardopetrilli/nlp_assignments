# NLP_Assignments

## Overview of the Tasks

This repository addresses two key challenges in sexism detection using Natural Language Processing (NLP):

### **[EXIST 2023 Task 1](https://nlp.uned.es/exist2023/)**  

🌟 *Objective*: Detecting and classifying sexism in textual data extracted from **tweets**.  

🔍 *Overview*:  
Our analysis compared the performance of **LSTM** and **Transformer models**, with **RoBERTa** significantly outperforming the Custom Model. This success is attributed to RoBERTa’s **larger number of parameters**, **pretraining on a more extensive corpus**, and **fine-tuning on the specific task**.  

✅ *Key Takeaways*:  
- Pre-trained transformer architectures like RoBERTa are highly effective for complex tasks such as **sexism detection**.  
- Overassociation of the term **‘woman’** with sexism, leading to systematic misclassifications.  

### **[EDOS Task A](https://github.com/rewire-online/edos)**  

🌟 *Objective*: Classifying sexist content in textual data extracted from **tweets**.  

🔍 *Overview*:  
This task explores **prompting techniques** using **Large Language Models (LLMs)** to assess their capability to **understand nuanced contexts** in sexist content and **classify complex and ambiguous cases** effectively.  

✅ *Key Takeaways*:  
- **Few-shot prompting** proves to be the most effective technique for this type of task.  
- The **Chain of Thought (CoT) technique** positively impacts model performance by enhancing reasoning capabilities.  
- Experiments on a smaller dataset (CLEF EXIST Task 1, 2023) highlight the **importance of fine-tuning**, which:  
  - Enables the use of **lightweight models** that outperform larger LLMs.  
  - Aligns with recent research findings (Bucher and Martini, 2024).  


## 📩 Contacts

- Francesco Baiocchi ([francesco.baiocchi2@studio.unibo.it](mailto:francesco.baiocchi2@studio.unibo.it))  
- Christian Di Buò ([christian.dibuo@studio.unibo.it](mailto:christian.dibuo@studio.unibo.it))  
- Leonardo Petrilli ([leonardo.petrilli@studio.unibo.it](mailto:leonardo.petrilli@studio.unibo.it))  

