# UiPath Timed RAG Demo

This project demonstrates a small but production-oriented RAG (Retrieval-Augmented Generation) workflow built with UiPath, focusing on latency measurement, prompt optimization, and orchestration.

---

## 🚀 Features

- Modular UiPath workflows
- Step-level timing for AI and non-AI activities
- Prompt size awareness
- Enterprise-style logging

---

## 🧠 Architecture

User Question  
→ Retrieve Documents  
→ Build Prompt  
→ LLM Call  
→ Grounding Check  
→ Final Answer + Timing Logs

---

## ⏱ Sample Timing Output
[AI_TIMING] Step=RetrieveDocuments Duration=2.1s
[AI_TIMING] Step=BuildPrompt Duration=0.4s Tokens=3800
[AI_TIMING] Step=LLM_Call Duration=11.6s Model=gpt-4
[AI_TIMING] Step=GroundingCheck Duration=3.2s

---

## 🎯 Purpose

This project shows how to measure and optimize AI latency in UiPath-based automation workflows.

---

## 👤 Author

Tanvi Gupta  
RPA Project Lead | Intelligent Automation
