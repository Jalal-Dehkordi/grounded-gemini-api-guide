# Gemini API Search Grounding Guide

![GitHub](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

This repository demonstrates how to use **Google Search Grounding** with Gemini API to fetch real-time, verified information from the web.


## 🔍 What is Search Grounding?

**Grounding** connects a language model to verifiable information sources, such as Google search results. It works similarly to **RAG (Retrieval-Augmented Generation)** but is done automatically in the Gemini API.

---

## 🆕 New Features in Gemini 2.0

- The **Gemini 2.0 Flash** model includes a generous Google Search quota (in the **Free** version).
- Older models like **Gemini 1.5** require payment or the use of **AI Studio** to enable Grounding.


## 🚀 Quick Start
1. **Get an API Key** from [Google AI Studio](https://aistudio.google.com/app/apikey).  
2. **Run the Jupyter Notebook** [`google-search-grounding-with-gemini-api.ipynb`](google-search-grounding-with-gemini-api.ipynb).  

## Using AI Studio for Grounding

### Steps to Enable Grounding:
1. **Log in to AI Studio**:
   - Go to [AI Studio](https://makersuite.google.com) and enter the **New chat** environment.
   - Use the `gemini-2.0-flash` or `gemini-1.5-flash` models.
2. **Enable Grounding**:
   - In the right sidebar, go to **Tools** and enable **Grounding**.

You can easily test the impact of search grounding in Google AI Studio by asking a question, observing the initial response without grounding, then toggling the "Google Search Grounding" feature to see the enhanced response with cited sources and updated information - all within the same chat interface.
