# ARCHITECTURE OF AARUDHRA

*SYSTEM ARCHITECTURE*

The system architecture of the AARUDHRA mobile application is designed to deliver fast, simple, and reliable first-aid support to rural users, even in places with low internet connectivity. The architecture follows an offline-first model, where all essential first-aid instructions, icons, and emergency data are stored within the app itself so users can access help at any time.

The interface layer handles user actions through clear buttons, visuals, and Tamil audio guidance, making the app easy to use for people with different literacy levels. Behind this, the application logic processes every user request—such as selecting an emergency, playing text-to-speech instructions, updating health charts, or triggering reminders—and ensures a smooth flow across modules.

The data and service layer manages local storage, health logs, and offline content, while also connecting to online features like the hospital locator when internet is available. Together, these layers create a lightweight, efficient, and user-friendly architecture that supports quick decision-making, accurate guidance, and dependable emergency response for rural communities.

<img width="978" height="759" alt="image" src="https://github.com/user-attachments/assets/e3b3c53b-785a-42af-b71f-7c99e147a84e" />

# METHODOLOGY 

The methodology followed in this project is based on understanding how a rural user interacts with the application and designing the system step-by-step to support them during emergencies. The workflow begins with the user opening the app and reaching the splash screen, after which they are taken to the home screen. From here, the user chooses the module they need—First Aid, Hospital Locator, Chatbot, or Health Monitor. Each module has a simple flow that guides the user through the required information using icons, Tamil text, and audio instructions. For first-aid situations, the user selects a category like cuts, burns, fever, snakebite, headache, or stroke. The app retrieves the corresponding steps stored locally and presents them with audio support, ensuring quick help even without internet. In the Hospital Locator module, the system uses the user’s location and OpenStreetMap to display nearby hospitals. The Chatbot module receives a user’s question and returns a predefined answer along with optional Tamil text-to-speech. In the Health Monitor module, the user enters values like BP, heart rate, sugar level, and weight; the app stores these readings, generates graphs, and sets medicine reminders if needed. Every module includes a home icon to help users return easily to the main screen.

*ALGORITHM*


STEP 1 : Start the application and display the splash screen with the logo.

STEP 2 : After the splash duration, load the home screen (no login).


1)	HOME SCREEN OPTIONS :

STEP 3 : User selects one of the modules :

✶ FIRST-AID

✶ NEARBY HOSPITALS LOCATOR

✶ CHATBOT

✶ HEALTH MONITOR

(A HOME ICON IS AVAILABLE IN EVERY SCREEN TO RETURN HERE.)


2)	FIRST-AID MODULE :

STEP 4 : User selects a condition :

✶ CUTS

✶ BURNS

✶ FEVER

✶ SNAKE BITE

✶ STROKE

✶ HEADACHE

STEP 5 : App retrieves the matching tamil first-aid instructions.

STEP 6 : Show steps on screen and play audio using TTS.

STEP 7 : Allow next/previous navigation through the steps.

STEP 8 : If the user taps the home icon, return to home screen.


3)	NEARBY HOSPITALS LOCATOR :

STEP 9 : User selects nearby hospitals.

STEP 10 : Load web viewer and open the hospital/map link.

STEP 11 : Display nearby hospitals.

STEP 12 : On pressing the home icon, return to home screen.


4)	CHATBOT MODULE :

STEP 13 : User types a question.

STEP 14 : App checks the predefined Q/A list for a match.

STEP 15 : Display answer + play tamil TTS audio.

STEP 16 : User taps home icon to return to home screen.


5)	HEALTH MONITOR MODULE :

STEP 17 : User selects a module :

✶ BMI CALCULATOR

✶ MEDICINE REMINDER

✶ BP, HEART RATE, SUGAR LEVELS TRACKING

STEP 18 : If BMI calculator module is clicked, it asks for weight, height and age. after entering the data, it calculates your BMI and shows the status.

STEP 19 : If medicine reminder is clicked, the user needs to set the time, date and the name of the medicine and can save it, so it trigger timer and notifier at the correct time.

STEP 20 : Save values internally and update line charts for tracking.

STEP 21 : On pressing the home icon, return to home screen. 
