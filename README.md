# 📊 Coders of Delhi — Social Network Data Analysis Using Python

This project is a **Python-based data analysis and analytics simulation** focused on understanding **user behavior, connections, and content preferences** in a social-network-style platform called **CodeBook**.

The project emphasizes **data cleaning, structured analysis, and insight generation** using **pure Python**, demonstrating strong analytical thinking without relying on external libraries such as Pandas or NumPy.

---

## 📌 Project Overview

The objective of this project is to simulate real-world **data analyst tasks** such as:
- Cleaning raw and messy user data
- Exploring user connections and engagement patterns
- Analyzing relationships between users and content
- Generating meaningful insights from structured datasets

The dataset represents users, their connections, and liked pages, enabling **relationship and behavior analysis** commonly used in analytics and reporting workflows.

---

## 🎯 Business & Analytical Objectives

- Clean and standardize raw user data stored in JSON format  
- Analyze user connections to understand engagement patterns  
- Identify mutual connections to support **network-based insights**  
- Analyze page preferences to understand **content interest trends**  
- Simulate recommendation logic from an **analytical perspective**

---

## 🛠 Tools & Technologies

- **Python (Pure Python)**
- JSON data handling
- Core data structures (Lists, Dictionaries, Sets)
- Modular scripting for analytics workflows

> Note: No external data analysis libraries were used to emphasize logic, data handling, and analytical problem-solving skills.

---

## 📂 Project Structure

```

coders-of-delhi/
├── codebook_data.json              # Raw user dataset
├── cleaned_codebook_data.json      # Cleaned and standardized dataset
├── load_display_data.py            # Data loading and initial exploration
├── clean_data.py                   # Data cleaning and validation logic
├── people_you_may_know.py          # Mutual connection analysis
├── pages_you_might_like.py         # Content preference analysis
└── README.md

```

---

## 🔍 Key Analysis Performed

### 1️⃣ Data Cleaning & Preparation
- Removed duplicate user records  
- Handled missing and inconsistent values  
- Standardized data formats for reliable analysis  

### 2️⃣ User Connection Analysis
- Analyzed friend relationships between users  
- Identified **mutual connections** to understand network structure  

### 3️⃣ Content Preference Analysis
- Examined page-like behavior across users  
- Identified potential content interest patterns  

### 4️⃣ Insight Generation
- Highlighted users with higher engagement  
- Identified potential connection and content patterns useful for recommendations  

---

## 📈 Sample Analytical Output

```

User: Amit (ID: 1)
Connections: [2, 3]
Liked Pages: [101]

Potential Connections (Mutuals): [4]
Suggested Pages Based on Preferences: [103]

````

This output demonstrates how raw relational data can be converted into **actionable analytical insights**.

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/KrishnaTanwars/Coders-of-Delhi-DS-Project.git
cd Coders-of-Delhi-DS-Project

# Run scripts step by step
python load_display_data.py
python clean_data.py
python people_you_may_know.py
python pages_you_might_like.py
````

---

## 📌 Business Relevance

Although simplified, this project mirrors **real-world analytics scenarios** such as:

* User behavior analysis
* Network and relationship analysis
* Data cleaning pipelines
* Insight-driven recommendation logic

It demonstrates strong **foundational data analysis skills**, logical thinking, and the ability to extract insights from structured data.

---

## 📌 Final Note

This project showcases my ability to:

* Work with raw datasets
* Perform structured data cleaning and analysis
* Derive insights using logical and analytical approaches
* Apply Python effectively in **Data Analyst and Business Intelligence contexts**

---

## 🛡 License

This project is licensed under the **MIT License**.

---
