# FURUTRE_DS_03

📊 College Event Feedback Analysis
Internship Project - Data Science & Analytics
Analyze student feedback to uncover satisfaction trends and suggest improvements using survey data.

🎯 Project Objective
This project analyzes student feedback from various college events to:

Understand satisfaction levels

Perform sentiment analysis on textual responses

Visualize trends in ratings and feedback

Provide actionable recommendations for future event improvements

🗂️ Dataset
Collected via Google Forms

Exported to CSV format

Contains fields:

Event Name

Event Date

Overall Rating (1–5)

What did you like about the event? (Text)

What could be improved? (Text)

Would you attend again? (Yes/No)

Any other comments?

🛠️ Tools & Libraries
Python

Pandas

Matplotlib & Seaborn (for visualization)

TextBlob (for sentiment analysis)

WordCloud (for visual text insights)

Google Colab / Jupyter / VS Code

🚀 Project Workflow
Data Cleaning

Handle missing data

Drop empty feedback rows

Sentiment Analysis

Analyze polarity of textual feedback

Classify as Positive / Negative / Neutral

Visualization

Rating distribution

Sentiment distribution

WordCloud of what students liked

WordCloud of suggestions for improvement

Insights

Average event ratings

Most common feedback themes

Improvement areas

📈 Example Results
Average rating across all events: 4.2/5

72% Positive sentiment in feedback

Common suggestions: better time management, more variety, improved sound systems

📝 How to Run
Install dependencies:

pip install pandas seaborn matplotlib textblob wordcloud
python -m textblob.download_corpora
Run the notebook:

In VS Code or Jupyter:

main.ipynb
Or in Python script:

main.py
Place your CSV file in /data/feedback.csv

📚 Skills Learned
Data Cleaning & Preprocessing

Sentiment Analysis (TextBlob)

NLP Techniques

Data Visualization (Matplotlib, Seaborn, WordCloud)

Survey Data Analysis

 Acknowledgements
Internship at FUTURE INTERNS

Project under Data Science & Analytics Internship


