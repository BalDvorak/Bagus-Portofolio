# Bagus-Portofolio
Welcome to my GitHub portfolio! 🚀  
I’m passionate about **Data Science, Machine Learning, and Artificial Intelligence**.  
Here you’ll find some of my academic and personal projects that explore real-world problems using data-driven approaches.  

## 📂 Projects  

### 🔹 [Project 1: Fraud Prediction on Insurance Claim](#)
This project evaluates the use of **Neural Networks** for predicting fraudulent insurance claims.  
Insurance fraud is a critical issue that leads to significant financial losses.  
We built and tested a Neural Network model with different resampling strategies to handle class imbalance, and found that **Undersampling** gave the most reliable results.

- **Goal**: Predict fraudulent insurance claims using Neural Networks.  
- **Methods**: Data preprocessing, feature engineering, and resampling (SMOTE, undersampling, no resampling).  
- **Highlights**:  
  - Built an 8-layer Neural Network with ReLU and Sigmoid activation.  
  - Undersampling gave the best validation accuracy (**86%**) with strong fraud detection (Recall: **94%**).  
  - Provided insights on handling imbalanced datasets in fraud detection tasks.  

---

### 🔹 [Project 2: Sentiment Analysis of Whoosh High-Speed Rail](#)
This project analyzes public sentiment towards the **Whoosh Jakarta–Bandung High-Speed Rail** based on tweets from application X (Twitter).  
We compared traditional machine learning and transformer-based models, finding that **IndoBERTweet with data augmentation** gave the best results.

- **Goal**: Understand public sentiment (positive, neutral, negative) about Whoosh services.  
- **Dataset**: 7,500 tweets (Oct 2023 – Oct 2024), balanced across sentiment classes.  
- **Methods**: TF-IDF + SVM, IndoBERT, IndoBERTweet, and IndoBERTweet with data augmentation.  
- **Highlights**:  
  - Preprocessing with slang normalization, stemming, and stopword removal.  
  - SVM baseline accuracy: ~69%.  
  - IndoBERT: 77% accuracy.  
  - IndoBERTweet: 79% accuracy.  
  - ✅ IndoBERTweet + Data Augmentation: **90% accuracy**, strong across all metrics.  
- **Findings**:  
  - Users were positive about **service & ticket prices**.  
  - Negative sentiment dominated for **government policies & infrastructure issues**.  

🔗 **Resources**:  
- [Colab: Machine Learning Models](https://colab.research.google.com/drive/1EF_t7UhEvjYaA6xQsNkBgfTq2KnujigL?usp=sharing)  
- [Colab: IndoBERT & IndoBERTweet](https://colab.research.google.com/drive/1RxO9bNP3CIlEnRZLS8SCtpJiVRfXg7WB?usp=sharing)  
- [Colab: Data Augmentation](https://colab.research.google.com/drive/12Emc4HKPmcLzV0N6nwEECjmh1cvM3R16?usp=sharing)  


---

### 🔹 [Project 3: Sentiment Analysis of IKN on Platform X with IndoBERTweet](#)
This project analyzes public sentiment towards the relocation of Indonesia’s new capital city (IKN) using tweets from Platform X.  
We fine-tuned **IndoBERTweet**, a transformer model optimized for Indonesian social media text, to classify sentiments into positive, negative, and neutral.

- **Goal**: Understand public opinion on IKN by applying advanced NLP techniques.  
- **Dataset**: 2,177 tweets labeled as Positive, Negative, or Neutral.  
- **Methods**:  
  - Text preprocessing (cleaning hashtags, emojis, links, normalization).  
  - Resampling to handle class imbalance.  
  - Fine-tuning IndoBERTweet with Hugging Face Trainer API and early stopping.  
- **Results**:  
  - ✅ Accuracy: **96%**  
  - Precision/Recall/F1 all above **0.94** across sentiment classes.  
  - Positive sentiment dominates (~67%), followed by Negative (~31%), and Neutral (~2%).  
- **Insights**:  
  - **Positive**: Support for IKN development and social benefits.  
  - **Negative**: Concerns about infrastructure, economic risks, and governance.  
  - **Neutral**: Mostly factual or informational tweets.  

🔗 **Resources**:  
- [Google Colab Notebook](https://colab.research.google.com/drive/1ab80Rz4aHF2M7zeWLRJBVCvaWCpVTGDU?usp=sharing)  

---

### 🔹 [Project 4: Public Health Clustering in Coastal Areas](#)
This project applies **K-Means clustering** to analyze the level of public health across coastal regions using socioeconomic and health indicators.  
By clustering counties in the U.S. coastal areas, we identified distinct health patterns that can guide better policy interventions.

- **Goal**: Group coastal regions based on public health indicators to identify areas needing urgent attention.  
- **Dataset**: 155 U.S. coastal counties, 30 features (health, environment, socioeconomic indicators) from [County Health Rankings](https://www.countyhealthrankings.org).  
- **Methods**:  
  - Data preprocessing (duplicate removal, missing value imputation, scaling).  
  - Exploratory Data Analysis (EDA).  
  - K-Means clustering with **Elbow Method** & **Silhouette Score** for optimal K.  
- **Results**:  
  - Optimal clusters: **5**.  
  - Cluster insights:  
    - Cluster 0: Poor health, low life expectancy, weak economy.  
    - Cluster 1: High well-being, good healthcare access, high income.  
    - Cluster 2: Balanced health & social conditions, strong healthcare access.  
    - Cluster 3: Very low health, high obesity/smoking, economic inequality.  
    - Cluster 4: High-risk, severe health & socioeconomic issues.  
  - Silhouette Score ≈ **0.2** → moderate clustering quality.  


<img src="https://drive.google.com/uc?export=view&id=1VE8pU9a8PKfSS9cv_513zVO59c0-Wop-" alt="Project 4 Banner" width="700" />


🔗 **Resources**:  
- 📄 [Full Report (PDF)](./Laporan_Penelitian_PemodelanMatematis5B.pdf)  
---

## 🛠️ Tech Stack  
- **Languages**: Python, SQL  
- **Libraries & Frameworks**: Scikit-Learn, TensorFlow, PyTorch, Transformers, NLTK, Pandas, NumPy, Matplotlib, Seaborn  
- **Tools**: Jupyter Notebook, Google Colab, Git, SmartPLS  

---

## 📫 Connect with Me  
- LinkedIn: [Your LinkedIn Link]  
- Email: [Your Email Address]  

---
