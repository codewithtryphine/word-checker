# word-checker
# 🔍 Text Checker

A simple yet powerful Python tool that analyzes text — search for words, 
locate their position, and censor them automatically, no matter the case.

## ✨ What it does
- 🔡 **Case-Insensitive Search** — finds "Python", "PYTHON", or "python" the same way
- 📍 **Word Locator** — instantly returns the index position of a word in text
- ✅ **Existence Checker** — returns True/False if a word is present
- 🔒 **Auto-Censor** — replaces sensitive or unwanted words with `****`

## 💡 Why this matters
This mimics real features used in apps you use every day:
- Comment filters on Instagram/YouTube that block bad words
- Search bars (like Ctrl+F) that find text regardless of case
- Spam/keyword detection systems

## 🛠️ Built With
- Python 3
- String methods: `.lower()`, `.upper()`, `.find()`, `.replace()`, `in`

## 🚀 How to Run
```bash
python text_checker.py
