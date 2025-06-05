# 🎙️ Voice Email Agent using n8n + ElevenLabs

A voice-driven email automation system that lets users speak messages and have them automatically emailed — powered by **ElevenLabs** for voice input and **n8n** for workflow automation.

## 🔧 How It Works

1. **Voice Input**  
   The user records a voice message using ElevenLabs' voice-to-text API.

2. **Webhook Trigger (n8n)**  
   The transcribed message is sent to an n8n webhook.

3. **Email Lookup**  
   n8n checks a connected Google Sheet to find the recipient's email address.

4. **Send Email**  
   The message is formatted and sent as an email via n8n's email node (e.g., Gmail, SMTP, etc.).

---

## 📂 Project Structure

![Screenshot 2025-06-05 134323](https://github.com/user-attachments/assets/3ef81dc7-6bcd-42ea-adcc-120d3bfbbc41)
![Uploading Screenshot 2025-06-05 132318.png…]()
