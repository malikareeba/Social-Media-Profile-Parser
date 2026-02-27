# Social-Media-Profile-Parser
Python based parser that converts unstructured social media profile text into structured JSON and performs analytical insights on posts, followers, and categories.

# 📊 Social Media Profile Parser & Analyzer

A Python-based data processing project that converts unstructured social media profile text into structured JSON format and performs analytical insights on the extracted data.

---

## 📌 Overview

This project parses raw social media profile data stored in text files and transforms it into structured, machine-readable JSON.

The parser was developed using an initial dataset and successfully applied to a final dataset, demonstrating reusable and generalized parsing logic.

---

## 🎯 Objectives

- Extract structured information from unstructured text
- Clean and normalize numeric formats (e.g., 12.5K → 12500)
- Convert parsed data into JSON format
- Perform analytical queries on user data

---

## 📂 Datasets

The project works with:

- `initialdata.txt` – Used to build and test the parsing logic
- `finaldata.txt` – Used for final execution and analysis

Each dataset contains profile details such as:

- Username  
- Number of posts  
- Followers  
- Following  
- Category  
- Bio information  

---

## ⚙️ Features

- ✅ Text parsing and data extraction  
- ✅ Numeric normalization (K/M follower conversion)  
- ✅ JSON data generation  
- ✅ Identify:
  - User with maximum posts  
  - User with highest followers  
  - User following the most accounts  
  - Total users  
  - Unique categories  

---

## 🛠 Technologies Used

- Python 3  
- Jupyter Notebook  
- JSON module  
- File handling  
- String processing

## 📁 Project Structure
social-media-profile-parser/
├── project2.ipynb
├── initialdata.txt
├── finaldata.txt
├── data.json
├── README.md
└── .gitignore

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Social-  Media-Profile-Parser.git 
```
2. Navigate to the project folder:
    cd Social-Media-Profile-Parser

3. Open Jupyter Notebook:
   jupyter notebook

4. Run all cells in project2.ipynb



---

## 📁 Project Structure
