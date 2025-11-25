# 🛒 Market Basket Analysis on E-Commerce Sales

## 📌 Overview
Discovers frequent itemsets and association rules using Apriori algorithm.

## 🔍 Goal
Identify which items are bought together to improve cross-selling.

## 📊 Preprocessing
  * Removed duplicates
  * Grouped by TransactionNo
  * Applied TransactionEncoder for one-hot encoding

## 🧠 Apriori + Rules
  * min_support=0.003
  * Association rules with lift > 0.9
  * Top 10 rules sorted by lift

## 📊 Visuals
  * Top 10 frequent items
  * Rule-based visual plots (support, confidence, lift)

## 📂 Dataset
  * 20,507 rows
  * Fields: TransactionNo, Items, DateTime, Daypart, DayType

## 🛠 Tools
  * Python, MLxtend, Pandas, Matplotlib, Seaborn

## 🚀 How to Use
  * Load dataset
  * Apply Apriori
  * Generate and analyze rules
