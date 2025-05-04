##**📊 Benford's Law Analysis on Twitter Data**

This project investigates the applicability of Benford's Law to numerical data extracted from Twitter. Benford's Law predicts the frequency distribution of leading digits in naturally occurring datasets, where lower digits like '1' appear more frequently as the leading digit than higher digits like '9'.

🧠 **Objective:**
To analyze whether numerical values related to Twitter (e.g., followers count, friends count and id) conform to Benford's Law. This can be used for anomaly detection, data authenticity checks, or understanding natural vs manipulated growth patterns in social metrics.

📂 **Data Sources:**
Twitter mock data

**Fields analyzed include:**

Followers count

Friends count

ID

🔍 **Methodology:**
Data Cleaning: Removed null, zero, and irrelevant values.

Digit Extraction: Extracted the first significant digit from each numerical value.

Distribution Comparison:

Computed the actual distribution of leading digits.

Compared it with the expected Benford's distribution.

Statistical Tests: Applied Chi-square goodness-of-fit test and visual analysis.

📈 **Features:**
Supports visualization of digit frequency lineplots and bargraphs.

Charts for actual vs expected Benford distribution.

Supports analyzing separate features (followers vs friends vs ids).

Can be extended for anomaly detection.

🛠 **Technologies Used:**
Python

Pandas, NumPy

Matplotlib / Seaborn for visualization

SciPy for statistical tests

**📌Use Cases:**
Data Integrity Checks: Detect artificial inflation of metrics.

Behavioral Insights: Understand organic vs manipulated accounts.

Educational Tool: Demonstrates Benford's Law on real-world social media data.

