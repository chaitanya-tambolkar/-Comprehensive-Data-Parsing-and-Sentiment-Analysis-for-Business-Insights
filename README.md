# Comprehensive-Data-Parsing-and-Sentiment-Analysis-for-Business-Insights

This project focused on applying Natural Language Processing (NLP) techniques to perform sentiment analysis, uncovering insights such as the impact of COVID-19 on customer reviews to support structured business decision-making.Applied NLP (VADER) on 10K+ Google reviews to analyse sentiment and assess COVID-19’s impact. Built a Python pipeline improving efficiency by 30%, parsed semi-structured TXT/Excel data, and generated CSV/JSON outputs to extract key metrics for business insights.

Skills: Data Analysis · Python (Programming Language) · Natural Language Processing (NLP) · Exploratory Data Analysis (EDA) · VADER · Data Cleaning

Key Achievements:
• Parsing Raw Files: Collaborated on developing an end-to-end data pipeline using Python, improving processing efficiency by 30%. The system parsed semi-structured Google Reviews data across 15 TXT files with corresponding Excel metadata.
• Metrics Extraction: Delivered well-structured CSV and JSON outputs for over 10,000 reviews, extracting vital metrics such as review counts, response rates, and sentiment polarity for downstream analysis and visualization.
• NLP Implementation: Utilised the VADER (Valence Aware Dictionary for Sentiment Reasoning) model to analyse sentiment trends across customer feedback, identifying key behavioral shifts influenced by the COVID-19 pandemic and enabling data-driven strategic recommendations.


### 📚 Python Libraries

#### **Data Parsing & Transformation**
- `re` – Regular expressions for pattern matching in semi-structured text  
- `json` – Exporting structured data into JSON format  
- `pandas` – Data manipulation, cleaning, and aggregation  
- `datetime` – Time conversion (Unix → UTC format)  
- `os` – File handling and directory operations  

#### **Text Preprocessing & Feature Engineering**
- `nltk` – Tokenization, stopword removal, stemming (PorterStemmer)  
- `re` – Regex-based text cleaning  
- `collections` / `FreqDist` – Word frequency computation  
- `sklearn.feature_extraction.text` – CountVectorizer for sparse representation  
- `pandas`, `numpy` – Text data manipulation and vocabulary generation  

#### **Exploratory Data Analysis (EDA)**
- `matplotlib`, `seaborn` – Visualisation of sentiment and review trends  
- `pandas`, `numpy` – Data exploration and statistical summaries  
- `nltk.sentiment.vader` – Sentiment analysis and polarity scoring  
- `json`, `datetime` – Data extraction and date conversions  

#### ** Video Presentation**
- Tools: Google Slides, Canva, and screen recording for presenting EDA insights  
- Editing Software: OBS / PowerPoint Export / CapCut (for narration and visuals)

#### **Development History**
- Documentation and progress tracking compiled in `task5_130.pdf`
- Tools used: Google Docs, Google Colab version history, and PDF export  

---

As part of the project, this video presentation explains the **Exploratory Data Analysis (EDA)** performed on the Google Reviews dataset.  
It summarises the key insights, methodology, and visualisations derived from the data analysis phase.

🔗 **Watch the full presentation here:**  
[https://drive.google.com/drive/folders/18313XU9vvmJDmgo023uNeYQO0idB3yUB](https://drive.google.com/drive/folders/18313XU9vvmJDmgo023uNeYQO0idB3yUB)
 ** WORKFLOW **
        

             ┌────────────────────────┐
            │   Raw Data (TXT/XLSX)   │
            └────────────┬───────────┘
                         │
                         ▼
            ┌────────────────────────┐
            │  Task 1: Data Parsing  │
            │  → CSV / JSON outputs  │
            └────────────┬───────────┘
                         │
                         ▼
            ┌────────────────────────┐
            │ Task 2: Text Processing│
            │ → vocab.txt / countvec │
            └────────────┬───────────┘
                         │
                         ▼
            ┌────────────────────────┐
            │ Task 3: EDA & Insights │
            │ → Plots / Dashboards   │
            └────────────┬───────────┘
                         │
                         ▼
            ┌────────────────────────┐
            │ Task 4: Presentation   │
            │ → Video Explanation    │
            └────────────┬───────────┘
                         │
                         ▼
            ┌────────────────────────┐
            │ Task 5: Documentation  │
            │ → Development History  │
            └────────────────────────┘
