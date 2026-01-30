
<div align="center">


[![Typing SVG](https://readme-typing-svg.demolab.com?font=inter&pause=1000&color=F6B544&center=true&width=700&lines=Popularity+Recommendation+System;A+simple+AI-based+approach+to+recommend+popular+items;Baseline+model+for+Recommender+Systems)](https://git.io/typing-svg)



[![Python](https://img.shields.io/badge/Python-3.13+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.2.3+-3776AB?style=for-the-badge&logo=pandas&logoColor=white)](https://python.org)
[![NumPy](https://img.shields.io/badge/NumPy-1.26+-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.4+-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.9+-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.13+-4C72B0?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org)


</div>


# 📊 Popularity Recommendation System

This repository contains a **popularity-based recommendation system** implemented in a Jupyter Notebook. The goal of this project is to recommend **Book** based on their overall popularity (most viewed / highest interactions), without using personalized user history.

Popularity-based recommendations are a simple baseline in recommender systems that recommend the most popular items to all users. These systems are widely used as a reference model in research and industry because of their simplicity and ability to function without user history.


## 🧠 About

A **popularity-based recommender system** recommends the most frequently interacted items to users for example, the most watched movies or most bought products. Instead of modeling individual preferences, it assumes that the most popular items are likely to be of interest to the next user.

This project includes:
- A Jupyter Notebook (`Model.ipynb`) implementing the model
- A `Datasets/` folder for sample data
- An `images/` folder for visual assets


## 🚀 Features

✔️ Recommends top trending/popular items  
✔️ Works without historical user profiles  
✔️ Easy baseline for comparison with advanced models  
✔️ Suitable for cold-start scenarios (no user data) 


## 📁 Repository Structure

````
Popularity_Recommandations_System/
├── Datasets/
├── images/
├── Model.ipynb
├── .gitignore
└── README.md
````

## 🛠️ How It Works

1. Load the dataset containing items and interactions (e.g., ratings, views).  
2. Count interactions for each item.  
3. Sort items by frequency (popularity).  


## 📌 Why Use a Popularity Recommender?

Popularity recommendation is among the **simplest recommender approaches** and serves as a **baseline model** to compare against more complex systems. It does not require user history and can work immediately on new platforms.

**Pros**
- Works without individual user data  
- Fast and scalable  
- Good baseline to measure improvement

**Cons**
- Not personalized  
- Repeats similar recommendations for all users

