# Smart-Medication-Reminder
Building AI course project
--------------------------------------------------------------------------------------------------------------------------------------
📝 Summary
This project presents a mobile-based Smart Medication Reminder application developed using Python and the Kivy framework. It aims to assist patients, elderly individuals, and caregivers in managing medication schedules effectively by providing daily alerts, Arabic language support, and customizable dose-time settings. The app also includes sound notifications, and a settings interface to modify reminders with ease.
--------------------------------------------------------------------------------------------------------------------------------------
🧠 Background
Forgetfulness in taking medications on time is a common challenge, especially among elderly people, patients with chronic diseases, and busy individuals. Missing doses may lead to treatment failure, health deterioration, or hospitalization.

Traditional solutions like alarms or written schedules lack flexibility, daily customization, and often don't support multilingual users, especially Arabic speakers. Hence, this application is designed to fill that gap with user-friendly UI, Arabic support, and daily recurring reminders.
--------------------------------------------------------------------------------------------------------------------------------------
📱 How is it used?
User Interface: The user adds medication name and time via a simple form.

Daily Reminders: The app sends a notification with sound at the set time, every day.

Settings Screen: Users can access an “Edit Medications” screen to update dosage times.

Multilingual Support: The interface is in Arabic, with right-to-left text and custom fonts.

Future Use: It can be converted to an Android APK for real-world deployment.
--------------------------------------------------------------------------------------------------------------------------------------
📊 Data Sources and AI Methods
Local Data Storage: Currently, data is stored in-memory (during app runtime). Future upgrades may include SQLite or cloud storage.

No AI used yet: But AI features such as reminder optimization, health prediction, or voice interaction can be integrated using libraries like transformers, spaCy, or speech-to-text APIs.
--------------------------------------------------------------------------------------------------------------------------------------
⚠️ Challenges
Persistent Storage: Data loss occurs when the app closes (pending implementation of file/database storage).

Cross-platform Compatibility: Playsound and notifications behave differently on Android vs desktop.

User Interface on Small Screens: Requires optimization for smaller mobile devices.

Background Running on Android: Needs service handling to ensure reminders work even when the app is minimized.
--------------------------------------------------------------------------------------------------------------------------------------
🚀 What’s Next?
Add persistent storage (SQLite or JSON).

Allow deleting medications.

Enable voice commands to add/edit reminders.

Add custom sound selection for each medicine.

Convert to APK and deploy on Android.

Possibly integrate AI-powered health assistant for medication recommendations.
--------------------------------------------------------------------------------------------------------------------------------------
Acknowledgments
No sources used

