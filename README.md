# ChatGPT-Reviews-Analysis

**Project Overview**  
This project analyzes **customer reviews of ChatGPT** to uncover insights about user satisfaction, feature requests, and critical issues.  

The goal is to:  
- Understand **general sentiment** expressed by users.  
- Measure the **strength of opinions (subjectivity)**.  
- Identify **positive and negative features** frequently mentioned.  
- Explore **trends in feedback over time**.  

---

**Technologies Used**  
- **Python** (pandas, numpy)  
- **NLP**: TextBlob  
- **Visualization**: matplotlib, seaborn  
- **Data Cleaning & Processing**: regex, Counter  

---

**Project Structure**  
ChatGPT_Review_Analysis
│── ChatGPT_review_analysis.ipynb # Main analysis notebook
│── chatgpt_reviews.csv # Dataset
│── README.md # Project documentation
│── requirements.txt # Python dependencies


---

**Analysis Steps**  

**1. Data Preparation**  
- Loaded ~196,000 reviews  
- Standardized column names  
- Cleaned missing values  
- Converted review dates to datetime  

**2. Sentiment Analysis**  
- Calculated **polarity** and **subjectivity** using TextBlob  
- Categorized reviews as **Positive, Neutral, or Negative**  
- Compared sentiment with user ratings  

**3. Positive Features**  
- Extracted top positive keywords/phrases (e.g., *great app*, *very helpful*, *easy to use*)  

**4. Negative Features**  
- Identified most common complaints (e.g., *too slow*, *wrong answer*)  
- Categorized issues into:  
  - Performance  
  - Features  
  - User Experience  
  - Accuracy  
  - Subscription  

**5. Neutral Reviews**  
- Classified neutral comments into:  
  - Feature requests  
  - Questions  
  - Positive/Negative leaning  
  - Truly neutral  

**6. Time-based Analysis**  
- Trends in review volume per month  
- Sentiment distribution changes over time 

---

**Key Insights**  
- Majority of reviews are **positive**, with users praising **accuracy** and **helpfulness**.  
- **Negative reviews** highlight **performance issues, accuracy gaps, and subscription pricing**.  
- **Neutral reviews** often hide valuable feature requests.  
- Review volume shows steady **growth over time** with sentiment fluctuations.  

---

**How to Run the Project**  

**1. Clone the repo:**  
   bash
   git clone https://github.com/devjulaniya1/ChatGPT-Reviews-Analysis.git
   cd hatgpt-review-analysis

**2. Install dependencies:**

pip install -r requirements.txt

**Open Jupyter Notebook:**

jupyter notebook ChatGPT_review_analysis.ipynb

Run the notebook cells in order.
