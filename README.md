# PersonalAssistant
This project is a hands-free AI assistant that listens to your voice, understands natural language using OpenAI, and takes actions like sending WhatsApp messages, managing Gmail &amp; Calendar, summarizing emails

🔥 Features
🎙️ Voice Command Recognition

Wake word detection

Offline + Hindi-English hybrid support

🤖 Natural Language AI Parsing

Converts your speech to structured JSON commands via GPT

📲 WhatsApp Integration

Sends WhatsApp messages using Twilio

📧 Gmail Integration

Send and read emails using Gmail API

📆 Google Calendar Automation

Create & fetch calendar events hands-free

🔁 Fully Modular

Add new commands easily with plug-and-play modules



main.py                           # Entry point — listens, parses, routes
modules/
  ├── voice_interface.py          # Listens for voice input
  ├── ai_parser.py                # GPT-based command parser
  ├── whatsapp_sender.py          # Sends WhatsApp messages via Twilio
  ├── email_handler.py            # Gmail read/send logic
  ├── calendar_scheduler.py       # Google Calendar support
  ├── summarizer.py               # Summarizes email content
  ├── google_contacts.py          # Gmail contact management
  ├── call_maker.py               # Placeholder for call logic
  ├── contacts.py                 # Local contacts JSON loader
  └── command_parser.py           # Maps parsed JSON to function calls
