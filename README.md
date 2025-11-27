# 🕵️‍♂️ CortexXSpy – Fraud Alert Voice Agent

CortexXSpy is a voice-based AI fraud detection agent built as part of the  
**Murf AI Voice Agent Challenge – Day 6**.

It simulates a real bank fraud prevention call using **only fake data**, ensuring safety while demonstrating how AI can automate fraud investigation processes.

---

## 🚀 Features

- 🎙 Voice-based fraud alert conversation
- 🏦 Simulates a real bank fraud prevention officer
- 📄 Uses a fake sandbox database for fraud cases
- 🔐 Safe customer verification using non-sensitive data
- 🚫 Never asks for real card numbers, PINs, or OTPs
- 🔁 Transaction confirmation (Safe / Fraud flow)
- 📊 Updates fraud case status in database
- 📦 Outputs final case report as JSON
- 🔊 Powered by **Murf Falcon TTS**

---

## 🗂 Sample Fraud Case Database

```json
{
  "userName": "John",
  "securityIdentifier": "JS-4921",
  "cardEnding": "4242",
  "amount": "₹14,850",
  "merchant": "ABC Industry",
  "location": "Hyderabad, India",
  "transactionTime": "2025-03-18 09:42 PM",
  "transactionCategory": "E-Commerce",
  "transactionSource": "alibaba.com",
  "securityQuestion": "What city were you born in?",
  "securityAnswer": "Chennai",
  "status": "pending_review",
  "outcomeNote": ""
}
