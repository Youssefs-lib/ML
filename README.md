<!-- Animated, Flashy GitHub README for Darija Sentiment Analysis -->

<!-- Typing animation -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=28&duration=4000&color=F75C7E&center=true&vCenter=true&width=800&lines=Darija+YouTube+Sentiment+Analysis;Saad+Lamjarred+Case;Public+Opinion+Mining+via+Machine+Learning" />
</p>

---

## 📖 Project Overview  

This project analyzes **YouTube comments in Darija (Moroccan dialect)** — written in **Arabic script** ** — to capture public sentiment on the **rape conviction of Moroccan singer Saad Lamjarred**.  

We built a **machine learning pipeline** to classify, analyze, and visualize reactions:  

- **Data Source:** YouTube API (comments from case-related videos)  
- **Dataset:** ~2600 manually labeled comments  and 10k unlabeled comments for analysis
- **Task:** Sentiment classification → `Positive` · `Negative` · `Neutral`  
- **Algorithm:** Support Vector Machine (SVM)  
- **Accuracy:** ~71% (80/20 train/test split)  

---

## 🛠️ Tech Stack  

<p>
  <img src="https://skillicons.dev/icons?i=python" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/TF--IDF-2E77BC?style=for-the-badge&logo=apache&logoColor=white" />
  <img src="https://skillicons.dev/icons?i=git,github" />
  <img src="https://img.shields.io/badge/YouTube_API-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white" />
</p>

---

## 🔬 Methodology  

### 1️⃣ Data Collection  
- Scraped comments using **YouTube Data API**  
- Focused on **case-related videos**  

### 2️⃣ Preprocessing  
- Normalization of **Arabic + Latin Darija text**  
- Tokenization + stop-word removal  
- **TF-IDF vectorization**  

### 3️⃣ Modeling  
- Trained an **SVM classifier**  
- **~71% accuracy** on test data  

### 4️⃣ Analysis  
- 📈 **Sentiment over time:** How positivity/negativity changed across dates  
- 🔍 **Clustering:** Found recurring discussion topics (support, accusations, music, justice)  
- ☁️ **Word Clouds:** Frequent terms in **supportive vs critical comments**  

---

## 📊 Results  

<p align="center">
  <img src="https://img.shields.io/badge/Accuracy-71%25-green?style=for-the-badge" />
</p>
<img width="580" height="500" alt="55" src="https://github.com/user-attachments/assets/19e58f4b-2479-4f6d-994d-4e27cdb10e2e" />
<img width="859" height="468" alt="download" src="https://github.com/user-attachments/assets/ff12e83b-9167-402b-affd-cdda98aab1b7" />
<img width="850" height="545" alt="download" src="https://github.com/user-attachments/assets/0481a51f-0c0d-47c7-be36-590db85d3d02" />




- **Positive, Negative, Neutral trends plotted** across videos  
- **Clusters revealed public narratives** around support vs accusations  
- **Word clouds** show contrast in supportive vs critical discourse:
  <img width="2020" height="1019" alt="1" src="https://github.com/user-attachments/assets/e2fcedf6-2ad9-44e2-943c-2df9a93d70e6" />
  <img width="2020" height="1019" alt="3" src="https://github.com/user-attachments/assets/bf7e494f-0cc5-4077-bb97-dd4262f7907e" />
  <img width="2020" height="1019" alt="2" src="https://github.com/user-attachments/assets/4e087664-3471-423e-8488-9cfb4090fbf3" />



---
