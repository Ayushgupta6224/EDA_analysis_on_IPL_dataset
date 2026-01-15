# EDA_analysis_on_IPL_dataset
**Exploratory Data Analysis (EDA) on IPL Dataset**
**Project Overview**

This project performs Exploratory Data Analysis (EDA) on an IPL batting dataset to analyze player performance in a single season.
The objective is to extract meaningful insights related to matches played, runs, averages, strike rates, boundaries, centuries, half-centuries, and consistency of players.

The entire analysis is implemented using Python and Jupyter Notebook.

**Dataset Used**

File name: IPL_Dataset.csv

Description:
The dataset contains batting statistics of IPL players including:

Player name

Matches played

Innings

Runs

Highest score

Average

Balls faced

Strike rate

Number of 4s and 6s

Centuries and half-centuries

Not outs

**Tools & Libraries**

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib – data visualization

Seaborn – statistical plots & heatmaps

Jupyter Notebook / VS Code

**Questions Solved in This EDA
Descriptive & Performance Analysis**

Maximum matches played by an individual player in a season.

Top 2 players with highest batting average (minimum 2 half-centuries).

Split player name into First Name and Last Name.

Cleaned Highest Score column (removed * and converted to integer).

Total number of centuries scored in the season.

Players with strike rate lower than the season’s average strike rate.

Correlation analysis between numerical features (Heatmap).

Players with Average > 50 and Strike Rate > 125.

Players with Average > 40 and Balls Faced > 100.

Players who scored at least one century (with visualization).

Players who scored at least 4 half-centuries.

Players with more than 45 boundaries and 10 sixes.

Visualization-Based Analysis

Histogram of matches played by players.

Histogram of balls faced by players.

Top 12 players with most runs in the season.

Players who played matches but did not bat.

Percentage of total runs scored via 4s and 6s (Top 5 players).

Top 5 players with highest Not-Out percentage.

Visualization of top 10 players with most sixes.

Scatter plot of Runs vs Balls Faced and relationship analysis.

**EDA Process Followed**

Imported dataset using Pandas.

Performed data inspection using head(), info(), and describe().

Cleaned and transformed columns (Highest Score, Player Names).

Created new calculated columns for deeper insights.

Applied filtering and aggregation logic.

Visualized patterns using histograms, bar charts, scatter plots, and heatmaps.

Derived insights from both numerical and visual analysis.

**Key Insights & Findings**

A small group of players consistently dominate in terms of runs, boundaries, and sixes.

Players with higher balls faced generally show a strong positive correlation with runs scored.

Strike rate and average together help identify impact players.

Not-out percentage highlights players who remain consistent and reliable finishers.

Boundaries (4s & 6s) contribute significantly to total runs for top-performing players.

**Conclusion**

This EDA project demonstrates how raw IPL batting data can be transformed into meaningful insights using Python.
The analysis helps in:

Identifying top performers

Understanding player consistency

Analyzing aggressive vs anchor batting styles

Supporting data-driven cricket analysis

This project can be extended further using:

Match-wise data

Bowling statistics

Predictive modeling
