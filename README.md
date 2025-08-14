🍽️ Swiggy Analytics – Delhi Restaurants

Exploratory Data Analysis (EDA) on Swiggy’s restaurant data for Delhi, uncovering patterns in cuisine types, pricing, ratings, and geographic zones.


📌 Project Overview

This project focuses on analyzing Delhi’s restaurant ecosystem using Swiggy data.
Key objectives:

Identify popular cuisines and their distribution across zones.

Compare pricing patterns by zone and location.

Highlight top-rated locations and restaurants.

Explore zone-wise diversity in the restaurant scene.

🗂 Dataset

Features include:

name – Restaurant name

cuisine – Primary cuisine(s) served

location / clean_location – Raw and cleaned locality names

zone – Mapped Delhi zone (North, South, East, West, Central)

rating – Average rating

cost2plates – Approximate cost for two people

Source: Publicly available Swiggy listings dataset (cleaned in notebook).

🛠️ Tech Stack

Python – Data cleaning, analysis, visualization

Pandas / NumPy – Data manipulation

Matplotlib / Seaborn – Data visualization


📊 Key Analysis

Restaurant Distribution by zone

Cuisine Popularity heatmaps & pivot tables

Cost Analysis (boxplots for zone & top locations)

Top Locations by Ratings

Top Restaurants by total ratings

🚀 How to Run Locally

Clone the repo

git clone https://github.com/your-username/swiggy-analytics.git
cd swiggy-analytics


Install dependencies

pip install -r requirements.txt


Run Jupyter Notebook

jupyter notebook


Open swiggy_analysis.ipynb and run cells sequentially.
