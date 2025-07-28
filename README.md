# ABCDEats Customer Segmentation Project

## Overview

This project was developed as part of the **Data Mining** course (Fall Semester 2024-2025) for the **Master in Data Science and Advanced Analytics** at **NOVA Information Management School**.

The main goal was to perform **customer segmentation** for the fictional food delivery company, **ABCDEats Inc.**, by analyzing customer data collected over three months from three different cities. The segmentation aims to support ABCDE’s marketing team in designing personalized strategies based on customers’ behavioural and preference profiles.

---

## Project Description

Customers were segmented from two main perspectives:
- **Behaviour-based segmentation:** analysing ordering patterns and habits.
- **Preference-based segmentation:** focusing on cuisine preferences and product choices.

The final goal was to combine these perspectives into a comprehensive segmentation that helps create targeted marketing campaigns.

---

## Dataset

The dataset contains aggregated customer-level data over a three-month period, including:
- Unique customer identifiers
- Demographic data (age, region)
- Order history (number of vendors, products, timestamps)
- Promotion and payment details
- Cuisine-specific spending
- Order distribution by day of the week and hour

The raw data file is available at [`DM2425_ABCDEats_DATASET.csv`](./DM2425_ABCDEats_DATASET.csv).

---

## Project Structure

- `notebooks`: Contains all Jupyter notebooks for Exploratory Data Analysis (EDA), customer segmentation, and model building.

- `data`: Includes the original dataset (DM2425_ABCDEats_DATASET.csv) and any processed data files used during analysis.

- `models`: Stores saved models and clustering objects generated during the segmentation process.

---

## Key Steps and Results

1. **Exploratory Analysis:** Identification of patterns and treatment of missing data and outliers.
2. **Preprocessing:** Normalization, encoding, and feature engineering.
3. **Clustering:** Evaluation of multiple algorithms (K-Means, Hierarchical, etc.) and selection of the optimal number of clusters.
4. **Cluster Profiling:** Detailed description of each segment in terms of behaviour and preferences.
5. **Business Applications:** Suggestions for personalized marketing campaigns and future monitoring.
