# 🧠 Toxic Behavior in Reddit Gaming Communities

This project investigates user interactions in gaming subreddits to detect toxic behavior using network and sentiment analysis.

---

## 📌 Project Objective

- Detect toxic users who disrupt online community engagement.
- Recommend user removal strategies to improve sentiment without affecting network structure.

---

## 🔍 Data Overview

Data extracted from **5 gaming subreddits** between Jan 1 – Apr 15, 2025, using Reddit’s API via `asyncpraw`.

**Key Features:**
- Submission & Comment IDs
- Author Metadata (source & target)
- Sentiment Scores (using SVM)
- Post & Comment Scores
- Network Metrics: Degree, Clustering Coefficient, Betweenness, Reciprocity

---

## 🧰 Tools & Technologies Used

| Category             | Tools/Tech                  |
|----------------------|-----------------------------|
| Data Scraping        | Python, `asyncpraw`         |
| Data Cleaning        | Excel, Power Query          |
| Sentiment Analysis   | VADER, SVM                  |
| Network Analysis     | Gephi                       |
| Visualization        | Matplotlib, Seaborn         |

---

## 📈 Key Methods

- **Network Analysis**: Used Gephi to explore community structure, modularity classes, and ego networks.
- **Sentiment Analysis**: SVM model with scores from 0 (very negative) to 1 (very positive).
- **Toxicity Indicators**: Broadcast users, low reciprocity, low clustering coefficient.

---

## 🖼️ Sample Visuals

See the `/visuals` folder for:
- Modularity Class Plots
- Ego Networks of key users
- Degree & Sentiment Distributions

---

## 🧪 Results Summary

- Identified 10 toxic users across communities.
- Removed isolated broadcast users to improve average sentiment.
- Preserved main community structures during filtering.

---

## 📂 Project Structure

