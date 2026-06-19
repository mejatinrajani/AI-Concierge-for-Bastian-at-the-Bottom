# Quick Setup Guide

## Prerequisites

- Python 3.8+
- pip (Python package manager)

## Step 1: Get Your API Key

1. Visit [console.groq.com](https://console.groq.com)
2. Sign up or log in
3. Create a new API key
4. Copy your API key

## Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

## Step 3: Set Your API Key

Create a `.env` file in the project root directory:

```
GROQ_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your actual Groq API key from Step 1.

## Step 4: Run the App

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`

---

That's it! You're ready to go. 🚀
