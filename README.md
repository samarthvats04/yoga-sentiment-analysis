# 🧘‍♀️ Mood-Based Yoga Session Recommendation

This project combines the power of **Natural Language Processing** and **Wellness Tech** to create a system that recommends yoga sessions based on the user's current **mood**. By analyzing textual input using sentiment analysis, the system intelligently maps emotions to specific yoga routines designed to improve well-being.

---

## 📌 Project Highlights

- 🔍 **Sentiment Analysis** using a pretrained transformer-based model.
- 🧘‍♂️ **Yoga Session Recommendation** system tailored to user's mood.
- 🤖 Designed using Python, HuggingFace Transformers.

---

## 🚀 How It Works

1. **Input**: User enters a sentence or phrase describing how they feel (e.g., "I feel stressed and anxious").
2. **Sentiment Detection**: 
   - Text is passed through a pre-trained transformer model (`distilbert-base-uncased-finetuned-sst-2-english`) to detect whether the sentiment is `positive` or `negative`.
3. **Mood Mapping & Yoga Recommendation**:
   - Based on sentiment and keywords, a suitable yoga routine is selected from a predefined mapping.
   - Example: A `negative` sentiment may recommend a calming "Stress Relief Yoga" session.

---

## 🔧 Tech Stack

- Python 🐍
- NLP (nltk)
- HuggingFace Transformers 🤗  
- PyTorch 🔥  
- Matplotlib 📈  

---
