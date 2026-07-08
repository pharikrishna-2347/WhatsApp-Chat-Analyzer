# 💬 WhatsApp Chat Analyzer

A Streamlit-based web application that analyzes exported WhatsApp chat files and provides meaningful insights through interactive visualizations and statistics.

## 🌐 Live Demo

🔗 **Try the application here:**
[https://phk-whatsapp-chat-analyzer-zzypweg3nkymhvspx6fj8x.streamlit.app/](https://phk-whatsapp-chat-analyzer-zzypweg3nkymhvspx6fj8x.streamlit.app/)


## 🚀 Features

* 📊 Chat Statistics

  * Total messages
  * Total words
  * Media shared
  * Links shared

* 📅 Timeline Analysis

  * Monthly message timeline
  * Daily message timeline

* 📈 Activity Analysis

  * Most active day of the week
  * Most active month
  * Weekly activity heatmap

* 👥 User Analysis (Group Chats)

  * Most active users
  * User contribution percentages

* ☁️ Word Analysis

  * Word Cloud
  * Most frequently used words

* 😊 Emoji Analysis

  * Most used emojis
  * Emoji distribution pie chart

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Pandas
* Matplotlib
* Seaborn
* WordCloud
* URLExtract
* Emoji

---

## 📂 Project Structure

```
WhatsApp-Chat-Analyzer/
│── app.py
│── helper.py
│── preprocessor.py
│── stop_hinglish.txt
│── requirements.txt
│── README.md
```

---

## 📥 How to Use

1. Export a WhatsApp chat **without media**.
2. Open the Streamlit application.
3. Upload the exported `.txt` file.
4. Select **Overall** or a specific participant.
5. Click **Show Analysis** to view detailed insights.

---

## ▶️ Running the Project Locally

Clone the repository:

```bash
git clone https://github.com/<your-username>/WhatsApp-Chat-Analyzer.git
```

Navigate to the project folder:

```bash
cd WhatsApp-Chat-Analyzer
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 📊 Insights Generated

* Total chat activity
* User-wise participation
* Daily and monthly messaging trends
* Weekly activity heatmap
* Most common words
* Word cloud visualization
* Emoji usage statistics
* Shared media count
* Shared links count

---

## 📸 Screenshots

Add screenshots of:

* Home page
* Top Statistics
* Monthly Timeline
* Activity Heatmap
* Word Cloud
* Emoji Analysis

---

## 📌 Future Improvements

* Sentiment analysis
* Chat response time analysis
* Message streak analysis
* Export analysis report as PDF
* Interactive Plotly visualizations
* Advanced filtering options

---

## 👨‍💻 Author

**Hari Krishna**

If you found this project useful, consider giving it a ⭐ on GitHub!
