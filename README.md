# 📊 WHATSAPP CHAT ANALYZER

## 📌 Overview
This project is a Python-based WhatsApp Chat Analyzer that transforms raw exported chat data into meaningful insights using data analytics and visualization techniques. It helps uncover communication patterns, user activity, and engagement trends from unstructured chat data.

---

## 🎯 Problem Statement
Analyzing WhatsApp chats manually is inefficient and time-consuming, especially for large datasets. This project aims to automate the process by converting raw chat data into structured insights that reveal user behavior and communication trends.

---

## 📂 Data Source
- Raw WhatsApp chat exported in `.txt` format
- Dataset size: 50K+ messages

---

## ⚙️ Tech Stack
- Python (Pandas, NumPy)
- Matplotlib
- Regular Expressions (Regex)
- Streamlit (for deployment)

---

## 🔧 Project Workflow

### 1. Data Collection
- Exported chat data using WhatsApp's "Export Chat" feature

### 2. Data Preprocessing
- Parsed unstructured text data using Regex
- Extracted key fields:
  - Date
  - Time
  - User
  - Message
- Converted data into structured Pandas DataFrame
- Handled:
  - Multi-line messages
  - Missing usernames
  - System messages

### 3. Feature Engineering & Analysis
- Total messages and word count
- Most active users
- Most used words (after removing stopwords)
- Emoji analysis
- Links shared
- Generated word cloud

---

## ⏳ Time-Series Analysis
- Converted timestamps into datetime format
- Extracted features:
  - Year, Month, Day
  - Hourly activity
  - Day-of-week trends

### Insights Generated:
- Message trends (daily/monthly)
- Peak chatting hours
- Most active days
- Long-term engagement patterns

---

## 📊 Visualization
- Bar charts:
  - Most active users
  - Word frequency
- Line charts:
  - Time-series trends
- Word cloud for frequent words

---

## 📈 Key Insights
- Identified peak user activity hours and days
- Detected most active participants in conversations
- Uncovered frequently used words and emojis
- Analyzed communication intensity over time

---

## 💡 Business Use Cases
- User behavior analysis for messaging platforms
- Engagement tracking and optimization
- Feature planning for chat-based applications
- Social interaction analysis

---

## 🌐 Deployment
- Built an interactive web app using Streamlit
- Users can upload chat files and get instant insights

---

## 🚀 How to Run

```bash
https://whatsapp-chat-analyzer-vihea7eupror6urjhnhwya.streamlit.app/
