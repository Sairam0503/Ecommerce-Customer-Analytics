# Ecommerce-Customer-Analytics
Digging into an online retail dataset to figure out customer habits who’s staying, who’s leaving, and what to do about it. It’s got the whole deal cleaning, plotting, clustering, and predicting all stuff. I’m proud to show off.
# overview
**Tools**: Python (Pandas, Numpy, Scikit-learn), Plotting (Matplotlib, SEABORN), Jupyter Notebooks, Git to keep it tracked 
**Goals**: Customer segmentation, chrun prediction, and actionable business insights.

## How to Run
1. Grab this repo: `git clone https://github.com/Sairam0503/Ecommerce-Customer-Analytics`
2. Install stuff: `pip install -r requirements.txt`
3. Get the dataset from [UCI](https://archive.ics.uci.edu/ml/datasets/Online+Retail) and put it in `data/`.
4. Open the notebooks in Jupyter and run them.

## Some Pics
- Sales trend: ![Sales Plot](plots/sales_over_time.png)
   *Shows sales spiking late 2011 maybe due holidays.*
- Clusters: ![Cluster Scatter](plots/cluster_scatter.png)
   *Groups customers by Recency and spend VIPs vs drop-offs!*
- What matters: ![Feature Importance](plots/feature_importance.png)
   *Recency rules churn biggest clue someone’s leaving*

## Project Highlights
Through this “Ecommerce Customer Analytics” project, I turned a raw, messy dataset into actionable insights over three months. I cleaned up 500k+ rows of sales data, built RFM scores, and found four customer types—like loyal VIPs (frequent, high-spending) and at-risk one-timers (inactive, low-spending). My Random Forest model predicted churn with an 85% ROC-AUC, pinpointing Recency as the top driver—20% of customers are at risk! Sales peak late-year (holiday boost!), and the UK dominates revenue. I delivered business ideas—loyalty perks for VIPs, re-engagement discounts for drop-offs—showing end-to-end analytics skills from data wrangling to modeling.

## Project Journey
This project was my dive into e-commerce data. Starting December 2024, I hit hurdles—like missing openpyxl throwing errors (fixed with a quick install) and scaling RFM wrong at first (caught it with describe()). Cleaning 135k rows of missing IDs was a slog, and picking four clusters took some elbow-plot guesswork. My churn model leaned heavy on Recency maybe too much but hit 85% accuracy. Finally, I had a polished GitHub repo with plots and insights, proving I can wrestle data into real-world value!
