# 🏏 T20 Cricket Data Analysis & Team Selection

A data-driven T20 cricket analysis project built using **Python, Pandas, NumPy, Matplotlib, Seaborn, and Power BI** to analyze player performances and derive insights for selecting a balanced T20 team.

The project processes cricket match data, calculates player performance metrics, compares players across different roles, and presents the results through interactive visualizations and dashboards.

## ✨ Features

* Comprehensive analysis of T20 batting and bowling performances
* Player-wise performance comparison
* Analysis of runs, wickets, strike rate, economy, and averages
* Identification of high-performing and consistent players
* Role-based player analysis for team selection
* Exploratory data analysis using Python
* Interactive Power BI dashboard for visualizing insights
* Data-driven approach to building a balanced T20 team
* Visual comparison of players across multiple performance metrics

## 🛠️ Technologies Used

### Python

Used as the primary programming language for data cleaning, transformation, analysis, metric calculation, and exploratory data analysis.

### Pandas

Used for loading, cleaning, transforming, filtering, grouping, and aggregating the cricket datasets.

### NumPy

Used for numerical calculations and statistical operations during the analysis.

### Matplotlib & Seaborn

Used to create charts and visualizations for understanding player performance, trends, distributions, and comparisons.

### Power BI

Used to build an interactive dashboard that presents player statistics and analysis in a visually accessible format.

### Jupyter Notebook

Used as the development environment for performing the analysis and documenting the data-processing workflow.

---

## 📊 Dataset

The project uses T20 cricket match data containing information related to matches, players, teams, batting, and bowling performances.

The raw data is transformed into player-level statistics that can be used for performance comparison and team selection analysis.

The major attributes analyzed include:

* Player
* Team
* Runs
* Balls Faced
* Wickets
* Runs Conceded
* Overs
* Strike Rate
* Economy Rate
* Batting Average
* Bowling Average

> The exact columns depend on the dataset used in this repository.

---

## 🧹 Data Preprocessing

Before performing the analysis, the raw cricket data is cleaned and transformed.

The preprocessing workflow includes:

1. Loading the raw datasets using Pandas.
2. Checking the structure and quality of the data.
3. Handling missing and inconsistent values.
4. Removing duplicate or unnecessary records.
5. Standardizing player and team information.
6. Converting columns into appropriate data types.
7. Aggregating match-level information into player-level statistics.
8. Creating additional performance metrics required for the analysis.

This step ensures that the data is consistent and suitable for further analysis.

---

## 🧮 Performance Metrics

Multiple performance metrics are calculated to evaluate players instead of relying on a single statistic.

### 🏏 Batting Strike Rate

Measures how quickly a player scores runs.

```text
Strike Rate = (Runs Scored / Balls Faced) × 100
```

### 🏏 Batting Average

Measures the average number of runs scored per dismissal.

```text
Batting Average = Runs Scored / Number of Dismissals
```

### 🎯 Bowling Economy

Measures the average number of runs conceded per over.

```text
Economy Rate = Runs Conceded / Overs Bowled
```

### 🎯 Bowling Average

Measures the average number of runs conceded for each wicket taken.

```text
Bowling Average = Runs Conceded / Wickets
```

These metrics are analyzed together to obtain a broader understanding of player performance.

---

## 🔍 Analysis Performed

### 🏏 Batting Analysis

The batting analysis examines:

* Total runs scored by players
* Strike rate comparison
* Batting average
* Consistency of run scoring
* Top-performing batsmen
* Player performance comparison

This helps identify players who can contribute effectively in different batting positions.

### 🎯 Bowling Analysis

The bowling analysis focuses on:

* Total wickets
* Economy rate
* Bowling average
* Runs conceded
* Bowling performance comparison
* Top-performing bowlers

This helps identify bowlers who can contribute effectively in different phases of a T20 match.

### 🔄 All-Rounder Analysis

Players contributing in both batting and bowling are analyzed separately.

Their performance is compared across both disciplines to understand their overall contribution to a team.

### 👥 Team Selection Analysis

The final stage uses the analyzed performance metrics to identify suitable players for different roles.

The analysis considers roles such as:

```text
Opening Batsman
      ↓
Middle-Order Batsman
      ↓
All-Rounder
      ↓
Wicketkeeper
      ↓
Fast Bowler
      ↓
Spinner
```

The objective is not simply to select players with the highest individual statistics, but to analyze how different player profiles can contribute to a balanced T20 team.

---

## 🔄 Project Workflow

```text
Raw Cricket Data
       ↓
Data Loading
       ↓
Data Cleaning
       ↓
Data Preprocessing
       ↓
Feature Engineering
       ↓
Player-Level Aggregation
       ↓
Batting Analysis
       ↓
Bowling Analysis
       ↓
Player Comparison
       ↓
Role-Based Analysis
       ↓
Team Selection Insights
       ↓
Power BI Dashboard
```

---

## 📈 Dashboard

The analyzed data is visualized through an interactive Power BI dashboard.

The dashboard provides an overview of:

* Batting performance
* Bowling performance
* Player comparisons
* Performance metrics
* Player rankings
* Role-based analysis
* Team selection insights

### Dashboard Preview

Add your dashboard screenshot here:

```markdown
![T20 Analysis Dashboard](images/dashboard.png)
```

---

## 📊 Visualizations

Python visualizations are used during exploratory analysis to identify patterns and compare player performances.

Examples include:

* Top run scorers
* Top wicket takers
* Strike rate comparison
* Economy rate comparison
* Batting average comparison
* Bowling average comparison
* Player performance distributions

These visualizations help identify patterns before presenting the final insights through the Power BI dashboard.

---

## 💡 Key Insights

The analysis can be used to answer questions such as:

* Who are the highest run-scoring players?
* Which players have the highest strike rates?
* Who are the most effective bowlers?
* Which bowlers maintain a lower economy rate?
* Which players show strong performance across multiple metrics?
* Which players are suitable for different T20 roles?
* How can player statistics be used to build a balanced team?

### Sample Insight Format

```text
• Player performance varies significantly when evaluated across different metrics.
• Strike rate provides a different perspective from total runs when comparing batsmen.
• Bowling economy and total wickets provide complementary views of bowling performance.
• All-rounders can provide additional flexibility by contributing in both disciplines.
```

> Replace the sample insights above with the actual findings from your dataset before publishing the repository.


## ⭐ Skills Demonstrated

```text
Python
Pandas
NumPy
Data Cleaning
Exploratory Data Analysis
Feature Engineering
Data Visualization
Power BI
Statistical Analysis
Sports Analytics
Data-Driven Decision Making
```
