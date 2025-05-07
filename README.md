# airline-chatbot-flan-t5
FLAN-T5-based NLP chatbot for airline customer service
# Airline Chatbot using FLAN-T5 ✈️🧠

This project builds an interactive NLP chatbot for airline customer service using the FLAN-T5 model. It supports queries on flight changes, baggage rules, seat upgrades, and more.

## 🔍 Overview
- Model: FLAN-T5-base (Seq2Seq, fine-tuned)
- Data: Airline FAQs, bookings, and travel datasets (5,521 Q&A pairs)
- Evaluation: BLEU (0.362), METEOR, ROUGE
- Tools: Hugging Face Transformers, Weights & Biases, FuzzyWuzzy
- Platform: Google Colab (T4 GPU)

## 📁 Files Included
- `airlineschatboat.ipynb` — Main notebook with all steps
- `Airline Chatbot Project Report.pdf` — Final PDF report
- `evaluate_results.txt` — BLEU, METEOR, ROUGE evaluation
- `README.md` — This file

## 📊 Key Results
- BLEU Score: 0.362
- Validation Loss: 0.0015
- Real-time chatbot loop tested with flight-related queries

## 📌 Future Work
- Expand dataset coverage for pets & international policies
- Add voice/chat UI and deploy as a web app

## 🔗 W&B Training Logs
[View on Weights & Biases](https://wandb.ai/richricha4939-univerai/huggingface/runs/kj0i5oab)

---

© Richa Patel | NLP Final Project | May 2025
