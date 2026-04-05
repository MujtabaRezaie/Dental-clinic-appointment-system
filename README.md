# Dental-clinic-appointment-system (n8n)

This workflow automates appointment scheduling for a dental clinic using Telegram, AI, and Google services.

Users send their name, problem, and preferred date and time through Telegram. An AI agent processes the message, extracts the required information, and checks availability in Google Calendar. If a time slot is available, the appointment is created and saved in both Google Calendar and Google Sheets. If no slot is available or the selected day is Friday, the user receives a rejection message.

The system supports Persian input and automatically converts dates to Gregorian format. Appointment duration is 30 minutes, and the earliest available slot is selected based on user preference.

Requirements include n8n, Telegram Bot API, Google Calendar API, Google Sheets API, and Google Gemini API.

