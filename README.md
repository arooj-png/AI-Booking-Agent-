# AI Booking Agent - Voice Assistant Style

🎙️ “Hello! I’m your AI Booking Assistant. Tell me when you want to schedule, reschedule, or cancel an appointment, and I’ll take care of it.”  

Built entirely in **n8n**, this project makes booking feel like talking to a real assistant.

## Features

- 🗣️ **Voice-Style Interaction**: Conversations feel like you’re talking to a live assistant.  
- 📅 **Google Calendar Integration**: Automatically creates, updates, or cancels events.  
- 🤖 **AI Intent Detection**: Understands natural language requests.  
- 💬 **Messaging Support**: Works via WhatsApp, Telegram, or other platforms.  
- ⚡ **No-Code Automation**: Easy-to-use workflows in n8n.  

## How It Talks

1. **User Says Something**: “I want to book a meeting tomorrow at 3 PM.”  
2. **AI Understands**: Detects intent, date, and time.  
3. **Calendar Action**: Event is created in Google Calendar.  
4. **Assistant Confirms**: “Great! Your meeting is scheduled for tomorrow at 3 PM.”  
5. **Logging**: All interactions saved for tracking and improvement.

## Setup

1. Install n8n:
   ```bash
   npm install n8n -g
   n8n start
