# 📝 Project Title: Himalayan Expedition Success Analysis

A comprehensive statistical analysis of factors affecting summit success rates in Himalayan climbing expeditions, using the 2025 TidyTuesday dataset.

## 📁 Folder Contents

- `Himalayan.Rmd` – R Markdown file for data cleaning, analysis, and visualization  
- `README.md` – Project overview and structure

## 📌 Project Overview

### 🏔️ Background  
The Himalayas are known for their extreme altitudes and expedition challenges. This project explores how variables such as team size, oxygen usage, and seasonal timing affect the probability of successfully reaching a summit.

### 🎯 Objectives

- Determine the key predictors of summit success  
- Visualize trends across peaks, seasons, and years  
- Provide actionable insights for future climbers and researchers

## 📊 Methodology

### 🔍 Data Preprocessing

- Joined `exped` and `peaks` datasets via `PEAKID`  
- Filtered incomplete or implausible records  
- Created a binary variable for success based on `TERMREASON_FACTOR`  
- Selected key predictors: `TOTMEMBERS`, `SMTMEMBERS`, `O2USED`, `HEIGHTM`, `SEASON_FACTOR`, etc.

### 📈 Analysis

- Examined success rates by peak, season, and oxygen use  
- Visualized height vs success rate patterns  
- Investigated team size effects and expedition durations

## 🔍 Key Insights

- **Oxygen use is strongly correlated with higher summit success**  
- **Spring and Autumn** are the most favorable seasons for climbing  
- **Small-to-mid-sized teams** show higher success, possibly due to coordination advantages  
- Higher-altitude peaks significantly reduce the chances of summiting

## 🧠 Key Learnings

- Preprocessing and cleaning large-scale real-world datasets is critical  
- Exploratory data visualization can reveal important climbing patterns  
- Interpretability matters—simple plots and clear metrics help communicate findings

## 📄 Full Report

📑 Please see [Himalayan.html](file:///Users/chenzhijing/Desktop/DSA2101/Himalayan.html) for the complete analysis and visualizations.
