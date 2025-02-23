# **Twitter Sentiment Analysis Tool**

## **Overview**
This project is a real-time **Twitter Sentiment Analysis** tool built using **Python, NLP, Streamlit,** and **Nitter**. It allows users to analyze sentiments by either typing custom text or fetching live tweets from any **Twitter** profile—without relying on the **Twitter API**!

## **Features**
- Scrape live tweets using **`ntscraper`** (Nitter-based scraping)
- Perform **sentiment analysis** using a custom-trained **NLP** model
- Interactive **web-based interface** using **Streamlit**
- Real-time visualization of **sentiment trends**

## **Tech Stack**
- **Python**: Core programming language
- **ntscraper**: Scrapes tweets without the **Twitter API**
- **NLTK/TextBlob/VADER**: For **sentiment analysis**
- **Streamlit**: **Web application framework** for UI
- **Matplotlib/Seaborn**: **Visualization of sentiment trends**

## **Installation**
### **Prerequisites**
Ensure you have **Python** installed (>=3.7). Install dependencies using:
```bash
pip install ntscraper streamlit nltk textblob vaderSentiment matplotlib seaborn
```

### **Clone Repository**
```bash
git clone https://github.com/yourusername/twitter-sentiment-analysis.git
cd twitter-sentiment-analysis
```

## **Usage**
### **Run the Streamlit App**
```bash
streamlit run app.py
```

### **Analyzing Tweets**
1. **Custom Input**: Enter text and get **sentiment classification** (**Positive/Neutral/Negative**)
2. **Fetch Live Tweets**: Enter a **Twitter username**, and the app scrapes recent tweets to analyze **sentiments**

## **Project Structure**
```
.
├── app.py               # **Streamlit app**
├── sentiment_model.py   # **Custom sentiment analysis model**
├── scraper.py           # **Nitter-based tweet scraper**
├── requirements.txt     # **Dependencies**
├── README.md            # **Project documentation**
```

## **Sentiment Analysis Methodology**
- **TextBlob**: For **polarity and subjectivity analysis**
- **VADER**: Optimized for short text like **tweets**
- **Custom Model**: (Optional) Train a **machine learning model** using **NLP techniques**

## **Deployment**
### **Deploy on Streamlit Cloud**
1. Push the project to a **GitHub repository**
2. Go to [**Streamlit Cloud**](https://share.streamlit.io/)
3. Deploy the **repository**

### **Deploy on AWS (Optional)**
Use **AWS EC2** or **Lambda** to host the app for wider accessibility.

## **Future Improvements**
- Improve **sentiment classification** with a fine-tuned **ML model**
- Add support for **multilingual sentiment analysis**
- Display **time-series sentiment trends** for a user’s tweets

## **Contributing**
Pull requests are welcome! Please **fork the repository** and submit a **PR**.

## **License**
This project is **open-source** and licensed under the **MIT License**.

