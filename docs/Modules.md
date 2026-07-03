# 🧩 MODULES IMPLEMENTED

The **AARUDHRA** application is designed using multiple modules, each developed to support rural users during emergencies with simple navigation and Tamil-based guidance. Every module works independently but connects smoothly with the home dashboard to offer a complete and user-friendly experience.

The following modules were implemented during the development of the system:

---

# 🚀 SPLASH SCREEN

The **Splash Screen** is the first screen displayed when the user opens the app. It shows the application name and logo, creating a clean introduction before the main interface loads.

This module gives users a quick, smooth entry into the app and sets the visual identity of **AARUDHRA**. It also handles any initial loading processes before navigating to the **Home Dashboard**.

---

# 🏠 HOME DASHBOARD

The **Home Dashboard** is the central navigation screen of the application.

It presents all the major features in a simple layout with large icons and Tamil labels.

| 📱 Available Features |
|----------------------|
| 🩹 First Aid |
| ❤️ Health Monitor |
| 🤖 Chatbot |
| 🏥 Hospital Locator |

This design ensures that users of all literacy levels can easily choose the module they need.

The dashboard serves as the main control hub, allowing the user to move from one feature to another without confusion.

---

# 🩹 FIRST-AID MODULE

The **First-Aid** module provides step-by-step instructions for common emergencies such as:

- ✂️ Cuts
- 🔥 Burns
- 🤒 Fever
- 🐍 Snakebite
- 🤕 Headache
- 🧠 Stroke

Each category includes structured guidance along with Tamil text-to-speech audio so users can listen and follow the instructions even if they cannot read.

This module is designed to work fully offline, ensuring that emergency help is available anytime, anywhere.

It also includes visuals/icons to make instructions simpler and faster to understand.

---

# ❤️ HEALTH MONITORING MODULE

The **Health Monitoring** module helps users track their basic health parameters.

It includes:

- ⚖️ BMI Calculator for calculating healthy body weight ranges
- 💊 Medicine Reminder to notify users at specific timings
- ❤️ BP, Sugar, and Heart Rate Tracking with graphical charts

All data entered by the user is saved offline so they can monitor health progress over time.

This module supports daily self-care and encourages users to maintain regular health records.

---

# 🤖 CHATBOT MODULE

The **Chatbot** module provides quick answers to common first-aid and health-related questions.

It works using predefined responses to ensure accuracy and can speak out the answers using Tamil text-to-speech.

This makes it especially useful for rural users who prefer listening instead of reading.

The chatbot offers a simple, interactive experience where users can type a question and receive an instant response.

---

# 🏥 HOSPITAL LOCATOR MODULE

The **Hospital Locator** module helps users find the nearest hospitals in case they need professional medical support.

It uses OpenStreetMap integration to show nearby medical facilities on a map along with distance information.

When the internet is available, it loads real-time map data.

When offline, the app can still show saved hospital details.

This module guides users on where to go after giving immediate first-aid.

---

# 🔊 TTS INTEGRATION (TAMIL TEXT-TO-SPEECH)

**Tamil Text-to-Speech** is integrated throughout the application to support users who may have difficulty reading.

This module converts written Tamil instructions into clear spoken audio.

It is used in:

- 🩹 First-Aid Module
- 🤖 Chatbot Responses

TTS ensures that people with low literacy, elderly users, and children can still understand emergency instructions easily.

---

## 📌 Summary of Implemented Modules

| Module | Purpose |
|---------|---------|
| 🚀 Splash Screen | Displays the app logo and initializes the application |
| 🏠 Home Dashboard | Central navigation hub for all modules |
| 🩹 First-Aid | Offline emergency guidance with Tamil TTS |
| ❤️ Health Monitoring | BMI calculator, reminders, and health tracking |
| 🤖 Chatbot | Answers common health and first-aid questions |
| 🏥 Hospital Locator | Displays nearby hospitals using OpenStreetMap |
| 🔊 Tamil Text-to-Speech | Converts written instructions into spoken Tamil audio |
