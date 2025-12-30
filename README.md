# AutoCorrect & Word Suggestion System

A smart **AutoCorrect / Word Suggestion Engine** built using Python and Streamlit.  
It detects misspelled words and suggests the most probable correct spellings based on word frequency and edit-distance logic — similar to basic suggestion behavior in mobile keyboards.

---

## Features
- Detects misspelled English words  
- Suggests best possible corrections  
- Ranks words based on probability  
- Uses Peter Norvig’s Spell Correction logic  
- Simple & interactive web app using Streamlit  

---

## How It Works
1️ Loads a large English text corpus (`big.txt`)  
2️ Builds a vocabulary and calculates word frequency  
3️ Uses **Edit Operations** to generate possible corrections:
- Insert
- Delete
- Replace
- Swap

4️ Filters real dictionary words  
5️ Selects the **most probable correct word**

This approach is based on the **Noisy Channel Model + Edit Distance Algorithm**.

---

## Technologies Used
- Python
- Streamlit
- Regex (`re`)
- Collections Counter
- NLP Probability Concepts

---

## Installation

### 1️ Install Dependencies
```bash
pip install streamlit
