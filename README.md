 # 🎓 College Event Feedback Analysis

This project analyzes feedback from students about a college event using sentiment analysis, data visualization, and word cloud generation to understand what attendees liked and what can be improved.

---

## 📊 Project Overview

Using a CSV dataset collected from event attendees, this project performs the following tasks:

- **Data cleaning** and preprocessing
- **Sentiment analysis** on qualitative feedback
- **Rating distribution** visualization
- **Word clouds** for most common likes and suggestions
- **Summary statistics** including average rating and top suggestions

---

## 📁 Dataset

The project expects a CSV file named:

data/feedback.csv



The CSV should contain at least these columns:
- `Overall Rating` – Numeric rating (e.g., 1 to 5)
- `What did you like about the event?`
- `What could be improved?`

---

## 🛠️ Libraries Used

Install the required Python libraries using:

```bash
pip install pandas matplotlib seaborn wordcloud textblob
For TextBlob, also run:


python -m textblob.download_corpora
📈 Key Functionalities
✅ Data Cleaning
Drops rows with missing feedback

Resets DataFrame index

💬 Sentiment Analysis
Uses TextBlob to analyze polarity of feedback on “What did you like about the event?”

Classifies each entry as Positive, Negative, or Neutral

📊 Visualizations
Rating Distribution – Using Seaborn countplot

Sentiment Distribution – Count of sentiments from student feedback

Word Clouds:

What students liked

What could be improved

📌 Summary Stats
Total sentiment counts

Average event rating

Most common improvement suggestions

📷 Sample Outputs
Bar charts for rating and sentiment distribution

Word clouds highlighting keywords in feedback

Console output for sentiment counts and suggestions

📂 Folder Structure
arduino
Copy
Edit
├── data/
│   └── feedback.csv
├── feedback_analysis.ipynb  # or .py
├── README.md
🧠 Possible Improvements
Add time-series feedback if event spanned multiple days

Include demographic filters (year, branch, etc.)

Add sentiment analysis for suggestions as well

👨‍💻 Author
Ayus Das
BCA Student | Python Developer | AI Enthusiast
Helping colleges improve through data insights 🚀

📄 License
This project is for academic and educational use. Feel free to reuse or modify it with credit.


---

Let me know if you want:
- The file as downloadable `README.md`
- Sample `feedback.csv` format
- A `.ipynb` Jupyter Notebook version of your script for direct usage in VS Code or Google Colab
