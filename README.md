# Unveiling the Android App Market: Analyzing Google Play Store Data

## 📌 Project Overview
This repository contains the data analytics project completed as part of the **Oasis Infobyte Data Analytics Internship** (Task 8). The primary objective of this project is to clean, analyze, and visualize Google Play Store data to uncover key insights into the Android app market dynamics, user behavior, pricing strategies, and review sentiments.

## 📁 Repository Structure
* **`OIBSIP_DataAnalytics_8.ipynb`**: The complete Google Colab/Jupyter Notebook containing the Python source code, data cleaning processes, and visualization pipelines.
* **`datasets/`**: Directory containing the source dataset files (`apps.csv` and `user_reviews.csv`).
* **`README.md`**: Comprehensive documentation of the project.

---

## 🛠️ Tools & Libraries Used
The data pipeline and analytics dashboard were constructed entirely in Python using the following specialized ecosystem:
* **Pandas**: For robust data structures, handling structural configurations, and algorithmic manipulation.
* **NumPy**: For advanced mathematical computations and missing-field evaluations.
* **Matplotlib**: For baseline coordinate rendering and layout engines.
* **Seaborn**: For statistical, multi-variable color mapping and data visualizations.

---

## 🚀 Key Steps Performed

### 1. Data Preparation & Structural Integrity Cleaning
* Unzipped and validated structural inputs from the raw dataset archives.
* Identified and resolved variable abnormalities across missing value records.
* Extracted corrupted text flags and stripped characters (such as `+`, `,`, and `$`) from numeric fields.
* Formatted data categories explicitly into computational types (`int64` for `Installs` and `float64` for `Price`).

### 2. Category Exploration
* Computed categorical distribution footprints across market verticals.
* Constructed frequency charts showing that **Family**, **Game**, and **Tools** capture the largest volume shares in the market ecosystem.

### 3. Metrics Analysis (Ratings, Sizes, and Pricing)
* Modeled an app rating distribution curve showing strong left-skewed user satisfaction metrics centered heavily between $4.0$ and $4.5$.
* Applied logarithmic distribution scaling to map app physical size boundaries against active installation frequencies.
* Analyzed system monetization patterns, isolating an overwhelming market bias where **92.2%** of available utilities run as free-to-download software.

### 4. User Review Sentiment Analysis
* Performed a common-key dataset merge aligning core app entries with granular user evaluation scripts.
* Filtered out unquantifiable feedback parameters and built distribution models confirming that user market responses lean heavily toward positive sentiments.

### 5. Market Premium Dashboarding
* Isolated extreme edge-case pricing exceptions within premium brackets.
* Built analytical distributions showcasing pricing trends among paid applications alongside the identification of luxury application novelties.

---

## 📊 Key Insights Uncovered
* **Market Dominance:** The Google Play Store is saturated primarily with functional utilities and entertainment sectors (Family/Games).
* **Pricing Strategy:** Free applications form the bedrock of consumer reach, making up more than 92% of market offerings.
* **User Satisfaction:** App distribution platforms enjoy positive feedback ecosystems, with review loops trending significantly toward favorable user sentiments.

---

## 📑 Submission Details
* **Domain:** Data Analytics
* **Task Number:** 8
* **Organization:** Oasis Infobyte
* **Project Format Identifier:** OIBSIP_DataAnalytics_8
