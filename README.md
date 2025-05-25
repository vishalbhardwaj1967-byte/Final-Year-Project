# 💡 AI-Powered Personal Finance Tracker

An intelligent and user-centric platform designed to streamline and automate financial management — without relying on traditional bank integrations. Built using modern AI/ML techniques and natural language interfaces, this solution enables smarter financial decision-making through voice commands, receipt scanning, and predictive analytics.

---

## 🧠 Overview

In today’s fast-paced, digital-first world, many struggle with manual budgeting, tracking, and bank-dependent apps. This project offers a fresh approach — an AI-powered finance tracker that:

- Extracts transaction data from receipts using **Tesseract OCR**
- Categorizes spending using **FinBERT NLP**
- Supports **voice-based logging** via **Web Speech API** and **Stanza**
- Provides **AI-driven budget recommendations** using **Gradient Boosted Decision Trees**
- Performs **financial forecasting** using **Prophet** and **LSTM models**
- Manages **group/shared expenses**
- Sends **bill reminders** using **Celery**
- Displays **interactive dashboards and visualizations**

---

## ✨ Features

- 🧾 **Receipt Scanning** – Upload scanned receipts to extract transaction info via OCR.
- 🗣️ **Voice Logging** – Log expenses using natural voice input.
- 🔍 **NLP Categorization** – FinBERT classifies spending into intelligent categories.
- 📈 **Forecasting** – Prophet and LSTM forecast future income and expenses.
- 📊 **Insights Dashboard** – Visualizations for spending trends and budget status.
- 👥 **Group Expense Module** – Track shared expenses with friends/family.
- ⏰ **Reminders** – Get bill notifications and payment alerts via Celery tasks.
- 🔐 **Secure Access** – Session-based authentication ensures data privacy.

---

## 🛠️ Tech Stack

### 🔗 Frontend
- **HTML5**
- **Tailwind CSS**
- **JavaScript**
- **Web Speech API** (voice input)

### ⚙️ Backend
- **Python**
- **Django** (main web framework)
- **Celery + Redis** (asynchronous task scheduling)
- **Session-based Authentication**

### 🧠 AI/ML & NLP
- **Tesseract OCR** – Extract text from receipts
- **FinBERT** – Expense category classification
- **Stanza** – NLP processing of voice input
- **Gradient Boosted Decision Trees** – Budget prediction
- **Prophet + LSTM** – Time-series forecasting for financial trends
- **Pickle** – ML model serialization

### 💾 Database
- **PostgreSQL**

---

## 🚀 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/sugapriya-k/Final-Year-Project.git
   cd Final-Year-Project
