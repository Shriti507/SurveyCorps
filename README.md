# 📊 Benford's Law Analysis on Twitter Data

Ever wondered if Twitter metrics like follower counts and user IDs follow a natural pattern? This project explores whether **Benford’s Law**—a fascinating statistical rule—applies to numerical data from Twitter.

> 🧮 Benford’s Law states that in many naturally occurring datasets, **lower digits (especially '1')** are more likely to appear as the **first digit** than higher ones (like '9'). This project examines whether Twitter's data aligns with this distribution.

---

## 🧠 Objective

To analyze whether Twitter metrics—such as **follower counts**, **friend counts**, and **user IDs**—follow Benford’s Law.  
This can help in:

- Detecting **anomalies or suspicious patterns**
- Assessing **data authenticity**
- Differentiating between **organic** and **manipulated** growth

---

## 📂 Data Source

- 🔹 **Mock Twitter Data**

**Fields analyzed:**
- 👥 Follower Count  
- 🤝 Friend Count  
- 🆔 User ID

---

## 🔍 Methodology

1. **Data Cleaning**
   - Removed null, zero, and irrelevant values.

2. **Digit Extraction**
   - Extracted the **leading digit** from each numeric field.

3. **Distribution Comparison**
   - Calculated the actual frequency of leading digits
   - Compared with the **expected Benford distribution**

4. **Statistical Analysis**
   - Conducted a **Chi-Square Goodness-of-Fit Test**
   - Visualized actual vs expected digit frequencies

---

## 📈 Features

- 📊 **Line plots and bar graphs** for digit frequencies  
- 📉 Visual comparison between **actual vs expected** Benford distribution  
- 📌 Separate analysis for different fields (followers, friends, IDs)  
- 🚨 **Extendable for anomaly detection**

---

## 🛠 Technologies Used

- 🐍 **Python**
- 📦 Pandas, NumPy  
- 📊 Matplotlib, Seaborn (visualizations)  
- 📐 SciPy (statistical testing)

---

## 📌 Use Cases

- ✅ **Data Integrity Checks**: Detect metric manipulation or spammy activity  
- 🔍 **Behavioral Insights**: Analyze trends in natural vs. inorganic growth  
- 🎓 **Educational Tool**: Real-world demonstration of Benford’s Law  

---
