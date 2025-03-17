# Financial-Dispute-AI-Assistant
This project implements an AI-powered financial dispute resolution assistant using NVIDIA-backed Generative AI. It automates customer complaint handling for financial transactions, fraud detection, and chatbot-based support.

# Features
Automated Financial Dispute Resolution: AI generates professional resolutions for transaction disputes.
Real-Time AI Chatbot: Users can enter their transaction issues and receive AI-driven resolutions.
Fraud Detection: AI simulates a fraud risk scoring system for transactions.
Pre-trained LLM (BART): Uses a transformer model to generate natural language responses.
Gradio Web UI: Provides a web-based interface for user interaction.

# How It Works
1️⃣ Load Financial Dispute Data
A sample dataset of customer transaction issues is loaded, including:
Unauthorized transactions
Incorrect interest charges
Double withdrawals
Unrecognized vendor charges

2️⃣ Pre-trained AI Model
Uses facebook/bart-large-cnn for natural language dispute resolution.
AI understands financial transaction issues and suggests solutions based on regulatory compliance.

3️⃣ AI-Generated Resolutions
For each transaction dispute, the AI generates a customer-friendly response.

4️⃣ AI Chatbot Deployment
Integrated Gradio-based chatbot where users input their disputes and get instant AI-generated resolutions.

5️⃣ Fraud Detection Simulation
AI assigns risk scores to financial transactions.
Uses a randomized risk model to flag high-risk transactions.

# Installation & Usage
1️⃣ Install Dependencies

pip install torch transformers pandas gradio

2️⃣ Run the AI Dispute Assistant

python financial_ai.py

3️⃣ Use the Chatbot

Open the Gradio web interface.

Type a financial complaint (e.g., "I was charged twice for my purchase").

AI provides a response.

4️⃣ Test Fraud Detection

print(detect_fraud(5000, "New York", "Midnight"))

The system will flag suspicious transactions based on risk scoring.

# Future Enhancements
✅ Fine-tune AI on real bank complaint data for higher accuracy.
✅ Integrate with financial APIs (Visa, Mastercard, PayPal) for live data.
✅ Deploy on Cloud (AWS/GCP) for large-scale use.
✅ Train on multilingual datasets for global finance support.

# Conclusion
This project demonstrates how Generative AI can automate financial dispute handling. It can be extended for banks, fintech companies, and credit bureaus to reduce operational costs and improve customer experience.
