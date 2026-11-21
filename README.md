# 📊 Spread Locator: A Statistical Distribution Analysis Model

## 📌 Project Overview

**Spread Locator** is a Python-based statistical analysis project that focuses on understanding customer purchasing behaviour through transaction data from an e-commerce platform.

The project applies various probability distributions and statistical techniques to analyse transaction amounts, identify spending patterns, examine data distribution, and calculate probability insights.

It explores how statistical distributions can help understand transaction behaviour and support data-driven business decisions.

## 🎯 Project Objectives

- Understand different types of probability distributions.
- Analyse customer transaction amounts and spending patterns.
- Apply Bernoulli and Binomial distributions to transaction occurrences.
- Model daily transaction frequency using the Poisson distribution.
- Analyse transaction amounts using Log-Normal and Power Law distributions.
- Use Q-Q plots and normality tests to examine data distribution.
- Apply Box-Cox transformation to reduce skewness.
- Calculate Z-scores and the probability of transactions exceeding ₹5,000.
- Visualize Probability Density Function (PDF) and Cumulative Distribution Function (CDF).
- Compare statistical distribution models and derive meaningful insights.

## 📂 Dataset Description

The project uses the `spread_locator_dataset.xlsx` dataset containing e-commerce transaction information.

The dataset includes the following attributes:

| Column Name | Description |
|---|---|
| transaction_id | Unique identifier for each transaction |
| customer_id | Unique identifier for each customer |
| transaction_amount | Total transaction amount in ₹ |
| transaction_date | Date of the transaction |
| transaction_count | Number of transactions made by a customer in a given week |
| region | Customer's geographical region |
| transaction_status | Transaction outcome (Success/Fail) |

## 🛠️ Technologies & Libraries Used

- **Python** – Programming language
- **Jupyter Notebook** – Development environment
- **NumPy** – Numerical computations
- **Pandas** – Data manipulation and analysis
- **SciPy** – Statistical distributions and hypothesis testing
- **Statsmodels** – Statistical analysis and Q-Q plots
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization

## 📈 Statistical Analysis Performed

### 1. Bernoulli Distribution
Analysed transaction outcomes by calculating the probability of successful and failed transactions.

### 2. Binomial Distribution
Modelled weekly transaction counts using the Binomial probability distribution.

### 3. Poisson Distribution
Analysed the number of transactions occurring per day using the average daily transaction rate.

### 4. Log-Normal Distribution
Modelled positive transaction amounts to understand right-skewed customer spending patterns.

### 5. Power Law Distribution
Applied a Pareto distribution model to examine transaction amounts and identify potentially high-value transactions.

### 6. Q-Q Plot and Normality Testing
Used Q-Q plots and statistical normality tests to examine whether transaction amounts follow a normal distribution.

### 7. Box-Cox Transformation
Applied Box-Cox transformation to reduce skewness and make the transaction data more suitable for statistical analysis.

### 8. Z-Score and Probability Analysis
Calculated transaction Z-scores and estimated the probability of transaction amounts exceeding ₹5,000.

### 9. PDF and CDF Analysis
Visualized the Probability Density Function and Cumulative Distribution Function to understand transaction amount probabilities.

### 10. Distribution Comparison
Compared Log-Normal and Power Law models using AIC and Kolmogorov-Smirnov statistics to evaluate their relative fit.

## 📊 Visualizations

The project includes the following visualizations:

- Transaction Amount Distribution
- Bernoulli Distribution
- Binomial Distribution
- Poisson Distribution
- Log-Normal Distribution Fit
- Power Law Distribution Fit
- Q-Q Plot
- Original vs Box-Cox Transformed Distribution
- Q-Q Plot After Transformation
- Probability Density Function (PDF)
- Cumulative Distribution Function (CDF)

Each visualization is supported by statistical observations and interpretations.

## 📁 Project Structure

```text
Spread-Locator/
│
├── spread_locator_analysis.ipynb
│
├── spread_locator_dataset.xlsx
│
└── README.md
```

## ▶️ How to Run the Project

**Step 1:** Clone this repository.

```bash
git clone https://github.com/your-username/Spread-Locator.git
```

**Step 2:** Open the project folder.

```bash
cd Spread-Locator
```

**Step 3:** Install the required libraries.

```bash
pip install numpy pandas scipy statsmodels matplotlib seaborn openpyxl
```

**Step 4:** Open Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open `spread_locator_analysis.ipynb` and run all cells sequentially.

**Note:** Keep the Excel dataset in the same directory as the Jupyter Notebook.

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

- Understanding and implementing probability distributions.
- Performing statistical analysis using Python.
- Working with real-world-style transaction datasets.
- Identifying skewness and examining data normality.
- Applying statistical transformations.
- Calculating probabilities and Z-scores.
- Creating meaningful statistical visualizations.
- Comparing distribution models and interpreting analytical results.

## 📝 Conclusion

The Spread Locator project demonstrates how probability distributions and statistical techniques can be applied to analyse e-commerce transaction behaviour.

By using Bernoulli, Binomial, Poisson, Log-Normal and Power Law distributions, the project explores transaction occurrences, daily transaction frequency and customer spending patterns.

Additional techniques such as Q-Q plots, Box-Cox transformation, Z-score analysis, PDF and CDF provide deeper insights into the statistical characteristics of the dataset.

Overall, this project strengthens practical knowledge of Python, probability distributions, statistical analysis and data visualization.

---

**Project Name:** Spread Locator – A Statistical Distribution Analysis Model

**Domain:** Mathematics & Advanced Statistics | Data Analytics

**Tools:** Python, Jupyter Notebook, NumPy, Pandas, SciPy, Statsmodels, Matplotlib and Seaborn

**Project Type:** Academic / Practical Data Analysis Project
