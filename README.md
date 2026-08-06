# 💬 WhatsApp Chat Analyzer

A powerful **WhatsApp Chat Analyzer** built with **Python** and **Streamlit** that transforms exported WhatsApp chat files into meaningful insights and interactive visualizations.

This project analyzes chat statistics, user activity, timelines, emojis, links, word frequency, and generates beautiful charts and word clouds to help users better understand their conversations.

---

## 📌 Features

- 📊 Overall and Individual User Analysis
- 💬 Total Messages Count
- 📝 Total Words Analysis
- 🖼️ Media Messages Count
- 🔗 Shared Links Detection
- 📅 Monthly Timeline Visualization
- 📆 Daily Timeline Visualization
- 📈 Weekly & Monthly Activity Analysis
- 🔥 Most Active Users
- ☁️ Word Cloud Generation
- 📖 Most Frequently Used Words
- 😀 Emoji Usage Analysis
- 📅 Weekly Activity Heatmap
- 📱 Interactive Dashboard using Streamlit

---

## 📷 Dashboard Preview

![Dashboard](Whatsapp_Chat_Analyser/Screenshots/Dashboard.png)

---

## 📊 Statistics

![Monthly_Timeline](Screenshots/Monthly_Timeline.png)

---

## ☁️ Word Cloud

![Word Cloud](Screenshots/WordCloud.png)

---

## 😀 Emoji Analysis

![Emoji Analysis](Screenshots/Emoji_Analysis.png)
---

# 🛠️ Tech Stack

- **Python 3.13**
- **Streamlit**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **WordCloud**
- **Regex**
- **Emoji**
- **URLExtract**
- **PyCharm IDE**

---

# 📂 Project Structure

```
WhatsApp-Chat-Analyzer/
│
├── app.py
├── helper.py
├── preprocessor.py
├── stop_hinglish.txt
├── whatsappChatAnalyser.ipynb
├── requirements.txt
├── README.md
├── LICENSE
└── .venv/
```

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
```

```bash
cd whatsapp-chat-analyzer
```

---

## Create Virtual Environment (Optional)

### Windows

```bash
python -m venv .venv
```

Activate

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv .venv
```

Activate

```bash
source .venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually

```bash
pip install streamlit pandas matplotlib seaborn wordcloud emoji urlextract
```

---

# ▶️ Run the Application

Start the Streamlit server

```bash
streamlit run app.py
```

The application will automatically open in your default browser.

---

# 📥 Export WhatsApp Chat

Before using the application:

1. Open WhatsApp.
2. Open the chat you want to analyze.
3. Tap **More → Export Chat**.
4. Choose **Without Media**.
5. Save the exported `.txt` file.
6. Upload the file through the Streamlit dashboard.

---

# 📊 Dashboard Features

## 📈 Top Statistics

Displays

- Total Messages
- Total Words
- Media Shared
- Links Shared

---

## 📊 Monthly Timeline

![Monthly_Timeline](Screenshots/Monthly_Timeline.png)

Visualizes message activity month-wise.

---

## 📆 Daily Timeline

Shows the number of messages exchanged every day.

---

## 📊 Activity Map

Displays

- Most Active Day
- Most Active Month

![Activity Map](Screenshots/Activity_Maps.png)

---

## 🔥 Weekly Activity Heatmap

Interactive heatmap showing chat activity across weekdays and hourly time intervals.

---

## 👥 Most Busy Users

Shows

- Top contributors
- Message percentage
- User ranking

(Group chats only)

![MostBusy_Users](Screenshots/Most_Busy_Users.png)

---

## ☁️ Word Cloud

Generates a word cloud after removing stop words and common filler words.

![Word Cloud](Screenshots/WordCloud.png)

---

## 📖 Most Common Words

Displays the most frequently used words in the conversation.

---

## 😀 Emoji Analysis

Shows

- Emoji frequency table
- Emoji usage pie chart

---

# 📁 Input Format

The application accepts exported WhatsApp chat files in `.txt` format.

Example:

```
12/07/24, 9:15 PM - John Doe: Hello!
12/07/24, 9:16 PM - Jane: Hi 👋
```

---

# 📦 Required Libraries

```
streamlit
pandas
matplotlib
seaborn
wordcloud
emoji
urlextract
numpy
```

---

# 🧠 Project Workflow

```
WhatsApp Chat Export (.txt)
            │
            ▼
      Data Preprocessing
            │
            ▼
     Message Parsing
            │
            ▼
     DataFrame Creation
            │
            ▼
      Statistical Analysis
            │
            ▼
 Data Visualization & Charts
            │
            ▼
 Interactive Streamlit Dashboard
```

---

# 💡 Future Improvements

- 📱 Support WhatsApp Business Chats
- 🌍 Multi-language Support
- 📈 Sentiment Analysis
- 🤖 AI-based Conversation Summary
- ❤️ Relationship Insights
- 📊 Advanced Analytics Dashboard
- ☁️ Online Deployment
- 📤 Export Analysis as PDF
- 📧 Email Report Generation
- 🌐 User Authentication

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

See the **LICENSE** file for more information.

---

# 👨‍💻 Author

**Arpit Jain**

**B.Tech Artificial Intelligence Student**

Passionate about Artificial Intelligence, Machine Learning, Data Science, Computer Vision, Python Development, and Generative AI.

- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/your-profile

---

# ⭐ Show Your Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

It helps others discover the project and encourages future development.

---

## 🙌 Acknowledgements

- Streamlit
- Pandas
- Matplotlib
- Seaborn
- WordCloud
- Open Source Python Community

---

**Happy Coding! 🚀**
