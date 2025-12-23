# 💬 WhatsApp Chat Analysis Dashboard

> Transform your WhatsApp conversations into meaningful insights with interactive visualizations and comprehensive analytics.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.0+-red.svg)](https://streamlit.io/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [How to Export WhatsApp Chat](#-how-to-export-whatsapp-chat)
- [Usage](#-usage)
- [Learning Outcomes](#-learning-outcomes)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [Author](#-author)

---

## 🌟 Overview

Ever wondered who sends the most messages in your group? What time of day is your chat most active? Which emojis dominate your conversations? This **WhatsApp Chat Analysis Dashboard** answers all these questions and more!

Built with Python and Streamlit, this interactive web application processes exported WhatsApp chat files and presents comprehensive analytics through beautiful visualizations and insightful statistics.

---

## ✨ Features

### 📊 Top Statistics
Get instant insights at a glance:
- **Total Messages** - Complete message count
- **Total Words** - Word count across all messages
- **Media Shared** - Photos, videos, and documents
- **Links Shared** - URL count and analysis

### 👥 User Analysis
Deep dive into user behavior:
- **Overall Chat Analysis** - Group-wide statistics
- **Individual User Analysis** - Per-user insights
- **Most Active Users** - Leaderboard visualization
- **User Activity Patterns** - Contribution percentages

### 📝 Word Analysis
Understand conversation content:
- **Most Common Words** - Frequency distribution
- **Word Cloud** - Visual representation
- **Custom Stopwords** - Filter out common words
- **Interactive Bar Charts** - Top 20 most used words

### 😀 Emoji Analysis
Decode emotional expressions:
- **Emoji Usage Count** - Total emoji statistics
- **Most Used Emojis** - Top emoji rankings
- **Emoji Distribution** - Beautiful pie chart visualization
- **Per-User Emoji Patterns** - Individual emoji preferences

### 📅 Timeline Analysis
Track conversation trends over time:
- **Monthly Timeline** - Message volume by month
- **Daily Timeline** - Day-by-day activity
- **Trend Identification** - Spot peak activity periods
- **Time Series Visualization** - Interactive line charts

### 🕒 Activity Maps
Discover peak engagement times:
- **Weekday Analysis** - Most active day of the week
- **Monthly Patterns** - Busiest months identified
- **Hourly Heatmap** - 24-hour activity distribution
- **Day-Hour Heatmap** - Combined day and hour analysis

---

## 🎥 Demo

![WhatsApp Chat Analysis Demo](https://github.com/princesi22/whatsapp-chat-analysis/blob/master/whatsapp%20chat%20analysis.gif)

*Live demonstration of the dashboard in action*

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python** | Core programming language |
| **Streamlit** | Interactive web application framework |
| **Pandas** | Data manipulation and analysis |
| **Matplotlib** | Data visualization and plotting |
| **Seaborn** | Statistical data visualization |
| **Regular Expressions** | Text parsing and pattern matching |

---

## 📂 Project Structure

```
whatsapp-chat-analysis/
│
├── app.py                  # Main Streamlit application
├── preprocessor.py         # Data preprocessing functions
├── helper.py              # Analysis and visualization helpers
├── requirements.txt       # Project dependencies
├── README.md             # Project documentation
└── .gitignore            # Excluded files
```

### File Descriptions

- **`app.py`** - Main application interface and user interaction logic
- **`preprocessor.py`** - Handles chat file parsing, cleaning, and structuring
- **`helper.py`** - Contains all analysis functions and chart generation code
- **`requirements.txt`** - Lists all Python package dependencies

---

## 💻 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Setup Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/princesi22/whatsapp-chat-analysis.git
   cd whatsapp-chat-analysis
   ```

2. **Create Virtual Environment** (Recommended)
   ```bash
   # On macOS/Linux:
   python3 -m venv venv
   source venv/bin/activate
   
   # On Windows:
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Verify Installation**
   ```bash
   python --version
   streamlit --version
   ```

---

## 📱 How to Export WhatsApp Chat

Follow these simple steps to export your chat:

1. **Open WhatsApp** on your mobile device
2. **Navigate to the Chat** you want to analyze (group or individual)
3. **Tap the Three Dots** (⋮) in the top-right corner
4. **Select "More"** → **"Export Chat"**
5. **Choose "Without Media"** (recommended for faster processing)
6. **Save the `.txt` file** to your device
7. **Transfer the file** to your computer

### Supported Formats
- ✅ Android format: `DD/MM/YYYY, HH:MM - User: Message`
- ✅ iOS format: `[DD/MM/YYYY, HH:MM:SS] User: Message`

---

## 🚀 Usage

### Running the Application

1. **Start the Dashboard**
   ```bash
   streamlit run app.py
   ```

2. **Access the Interface**
   - The app will automatically open in your default browser
   - Default URL: `http://localhost:8501`

3. **Upload Your Chat File**
   - Click the file uploader in the sidebar
   - Select your exported `.txt` chat file
   - Wait for processing to complete

4. **Explore the Analytics**
   - Select "Overall" for group analysis or choose a specific user
   - Click "Show Analysis" button
   - Scroll through various visualizations and insights

### Analysis Options

**Overall Analysis** - View complete chat statistics and trends

**User-Specific Analysis** - Select any user from the dropdown to see:
- Their message count and word usage
- Their most common words and emojis
- Their activity patterns and timelines

---

## 📚 Learning Outcomes

This project demonstrates proficiency in:

### Technical Skills
- **Data Preprocessing** - Parsing complex text formats, handling edge cases
- **Data Analysis** - Statistical analysis, trend identification, pattern recognition
- **Data Visualization** - Creating meaningful charts with Matplotlib and Seaborn
- **Web Development** - Building interactive dashboards with Streamlit
- **Python Programming** - Clean code, modular design, best practices

### Data Science Concepts
- **Exploratory Data Analysis (EDA)** - Understanding data characteristics
- **Time Series Analysis** - Temporal pattern identification
- **Text Analytics** - Word frequency, sentiment indicators
- **Statistical Visualization** - Heatmaps, distribution charts, timelines

### Soft Skills
- **Problem-Solving** - Converting chat exports into structured data
- **User Experience Design** - Creating intuitive interfaces
- **Documentation** - Clear README and code comments
- **Project Management** - Organized file structure and version control

---

## 📸 Screenshots

### Dashboard Overview
*Top statistics and user selection interface*

### Timeline Analysis
*Monthly and daily message trends*

### Activity Heatmap
*Hour and day-wise activity patterns*

### Emoji Distribution
*Most used emojis with visual charts*

---

## 🎯 Future Enhancements

- [ ] **Sentiment Analysis** - Analyze message sentiment (positive/negative/neutral)
- [ ] **User Comparison** - Side-by-side comparison of two users
- [ ] **Export Reports** - Download analysis as PDF
- [ ] **Multi-Language Support** - Support for non-English chats
- [ ] **Advanced Filtering** - Filter by date range, message type
- [ ] **Response Time Analysis** - Calculate average response times
- [ ] **Conversation Topics** - Identify main discussion themes using NLP
- [ ] **Dark Mode** - Enhanced UI with theme options

---

## 🤝 Contributing

Contributions are welcome and appreciated! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Contribution Ideas
- Add new analysis features
- Improve visualization aesthetics
- Optimize processing speed
- Enhance documentation
- Fix bugs and issues

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

👨‍💻 Author

Prince Aspiring Data Analyst

🔗 Live Dashboard- https://github.com/princesi22/whatsapp-chat-analysis/blob/master/whatsapp%20chat%20analysis.gif



