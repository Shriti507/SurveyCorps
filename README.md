📊 **Benford's Law Analysis on Twitter Data**

This project investigates the applicability of Benford’s Law to numerical data extracted from Twitter. Benford’s Law predicts the frequency distribution of leading digits in naturally occurring datasets, with lower digits like ‘1’ appearing more frequently as the leading digit than higher digits like ‘9’.

🧠 **Objective:**
This project aims to analyze whether numerical values related to Twitter—such as follower counts, friend counts, and user IDs—conform to Benford’s Law. By examining the distribution of leading digits in these values, we can assess if they follow the expected pattern predicted by Benford’s Law. Such analysis can be useful for detecting anomalies, verifying data authenticity, and distinguishing between natural and manipulated growth patterns in social media metrics.

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

Compared with the expected Benford distribution.

Statistical Tests: Applied Chi-square goodness-of-fit test and visual analysis.

📈 **Features:**
Supports visualization of digit frequency line plots and bar graphs.

Charts for actual vs expected Benford distribution.

Supports analyzing separate features (followers vs friends vs IDs).

Can be extended for anomaly detection.

🛠 **Technologies Used:**
Python

Pandas, NumPy

Matplotlib / Seaborn for visualization

SciPy for statistical tests

**📌Use Cases:**
Data Integrity Checks: Detect artificial inflation of metrics.

Behavioural Insights: Understand organic vs manipulated accounts.

Educational Tool: Demonstrates Benford's Law on real-world social media data.

