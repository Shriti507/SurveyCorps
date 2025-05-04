📊 **Benford's Law Analysis on Twitter Data**

The goal of this project is to explore whether Benford’s Law applies to numerical data taken from Twitter. Benford’s Law is a statistical principle that describes how often each digit (1 through 9) appears as the first digit in naturally occurring datasets. Interestingly, it shows that lower digits—especially ‘1’—tend to appear more frequently as the leading digit than higher ones like ‘9’. By applying this law to data such as follower counts, friend counts, and user IDs from Twitter, the project aims to determine whether these values follow the expected pattern. This can help in identifying anomalies or understanding the authenticity and nature of social media metrics.

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

