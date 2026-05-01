# 🚢 Spark ML Pipeline for Titanic Survival Classification

## 📘 Overview
This project predicts the survival of passengers aboard the Titanic using Spark ML pipeline and feature engineering tools. The dataset description can be found on the [Kaggle website](https://www.kaggle.com/).

The workflow focuses on:
- Constructing a full Spark ML pipeline with feature engineering
- Using Spark SQL / DataFrames to maintain scalability and clean transformations
- Ensuring idempotency, so the notebook can be run repeatedly without errors
- Demonstrating how Spark ML handles preprocessing, vectorization, and model training in a unified pipeline

This project was a part of an MSBA course on Big Data Analytics as a practical introduction to Spark ML’s pipeline architecture while solving a classic classification problem.

---

## 🗃️ Dataset Uploading

### 1. Download and load data
- Create a Unity Catalog Volume `homework3` under the schema `spark` of the catalog `msbabigdata` (recreate them if not exists)
- Download `titanic.csv`
- Then, load the data into the Unity Catalog Volume `homework3`
- Create a Spark DataFrame `titanic` using the uploaded csv file

---

## ⚙️ Technical Workflow
- Create catalog and schema in Unity Catalog
- Upload the Titanic dataset into the appropriate volume
- Load the dataset into Spark DataFrames
- Apply feature engineering and preprocessing using Spark ML
- Build a unified pipeline for training and evaluation

---

## 🧠 Core Concepts Used
- Spark ML Pipelines
- Feature Engineering
- Spark SQL / DataFrames
- Preprocessing and Vectorization
- Model Training in a Unified Pipeline
- Idempotent notebook design

---

## 📊 Results
- AUC:      0.8209
- F1 Score: 0.7778
- Accuracy: 0.7840
These results show that the Spark ML pipeline performs well on the Titanic survival classification task while keeping the workflow scalable and reproducible.

---

## 🧪 Project Purpose
The goal of this project is to show how Spark ML can be used to build a scalable and repeatable machine learning workflow for a classic classification problem. It demonstrates how preprocessing, feature transformation, and model training can be combined into a single pipeline. The notebook also emphasizes clean data handling through Spark SQL and DataFrames.

---

## 🗂 Repository Structure
- SparkML-Titanic-Classification.ipynb
