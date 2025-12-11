# NCERT Content Extractor & Study Planner

## 📌 Overview
This project leverages **Python** and **LLMs (OpenAI/DeepSeek)** to automate the extraction of educational content from NCERT PDF textbooks. It transforms unstructured PDF data into structured formats (JSON & Excel) and intelligently generates a custom, day-wise study planner based on the user's available time.

## 🚀 Key Features
* **PDF Parsing:** Extracts raw text and relevant sections from textbook PDFs.
* **Data Serialization:** Converts extracted content into structured **JSON** and **Excel (.xlsx)** files for easy analysis.
* **AI-Powered Planning:** Uses dynamic prompts with DeepSeek/OpenAI to analyze the Excel data and create a tailored study schedule.
* **Customizable Duration:** Generates plans based on specific user-defined timeframes (e.g., 30 days, 2 months).

## 🛠️ Tech Stack
* **Language:** Python
* **AI/ML:** OpenAI API, DeepSeek
* **Data Handling:** Pandas (for Excel/JSON manipulation)
