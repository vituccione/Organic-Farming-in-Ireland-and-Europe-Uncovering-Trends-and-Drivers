# 🌱 Organic Farming in Ireland and Europe: Uncovering Trends and Drivers

This data science project investigates the adoption of organic farming across the European Union, using **Ireland** as a comparative baseline. It combines **agricultural policy analysis**, **sentiment mining**, and **unsupervised learning** to explore how **CAP funding**, **public perception**, and **regional policies** drive the growth of organic agriculture.

📄 Full Report: [`CA2_report.pdf`](./CA2_report.pdf)

---

## 🎯 Objectives

- Assess **CAP funding impact** on organic farming area growth across EU countries
- Analyze **public sentiment** toward organic farming via Reddit NLP
- Use **clustering and PCA** to classify countries by agricultural and socio-political indicators
- Identify Ireland’s position and provide **policy recommendations**

---

## 🧠 Key Methods

- **Exploratory Data Analysis (EDA)**
- **Hypothesis Testing** (Paired T-test, Wilcoxon, Friedman ANOVA)
- **Sentiment Analysis** (VADER, Logistic Regression, Naive Bayes)
- **Topic Modeling** (LDA)
- **Hierarchical and K-Means Clustering**
- **Principal Component Analysis (PCA)**
- **Dashboard Development** (Streamlit)

---

## 📊 Data Sources

- **CMEF Indicators Dataset** – CAP funding and organic farming metrics ([AgriData Portal](https://agridata.ec.europa.eu))
- **Reddit Public Posts** – Sentiment scraped from country-specific subreddits
- **Country Metadata** – Agricultural area, public funding, and sentiment metrics (aggregated by country)

---

## 🔍 Analysis Highlights

### 📈 CAP & Organic Farming

- Ireland shows **steady but modest growth** in organic farming area
- **Austria and Sweden** lead in CAP-supported adoption
- Ireland receives **among the lowest per-hectare support** in the EU

### 🧪 Statistical Testing

- No statistically significant difference in organic adoption between Ireland and Bulgaria (T-test & Wilcoxon)
- ANOVA/Friedman tests confirm **Romania’s rapid growth** vs. Ireland’s slow progress

### 💬 Sentiment Analysis

- Processed over **30,000 Reddit comments**
- **VADER and Logistic Regression** used to classify sentiment
- **Positive sentiment dominates**, especially in Austria and Denmark
- **Ireland shows moderate but improving sentiment trends**

### 🔁 Clustering Insights

- **Cluster 1**: High-growth, low-funding countries (e.g., Portugal, Bulgaria)
- **Cluster 2**: Established leaders with high CAP support (e.g., Austria, France)
- **Cluster 3**: Moderate growth, moderate sentiment (Ireland’s cluster)

---

## 🧱 Technologies Used

- Python (Jupyter, Pandas, NumPy, Scikit-learn)
- Natural Language Processing: NLTK, VADER, Gensim, TfidfVectorizer
- Clustering: Hierarchical (Ward), K-Means
- Topic Modeling: Latent Dirichlet Allocation (LDA)
- Visuals: Matplotlib, Seaborn, Plotly
- Dashboard: Streamlit
- Data Handling: Winsorization, Robust Scaling, Linear Interpolation
