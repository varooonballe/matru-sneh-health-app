Matru-Sneh Health

An offline-first Android maternal healthcare application designed for rural pregnant women to monitor fetal movement, nutrition, vaccinations, and pregnancy danger signs using a simple and accessible mobile interface.


---

Problem Statement

In many rural areas, expectant mothers rely on physical maternal health cards that are often lost or damaged. This can lead to:

Missed vaccinations

Poor nutrition tracking

Delayed health check-ups

Lack of awareness about pregnancy danger signs


Matru-Sneh Health provides a digital healthcare companion that works even without internet access.


---

Features

Kick Counter

Tracks fetal movement

Debounce protection prevents accidental double taps


Nutrition Checklist

Tracks healthy local foods:

Ragi

Greens

Pulses

Milk



Vaccination & Check-up Reminders

Reminder scheduling using WorkManager

Works even after device reboot


Danger Sign Alert System

Alerts for:

Severe headache

Swelling

Reduced fetal movement



Weekly Baby Growth Updates

Kannada pregnancy guidance using Generative AI


Offline-first Storage

Uses Room Database for persistent local storage


Bilingual Support

Kannada and English language support



---

Tech Stack

Kotlin

Android Studio

Jetpack Compose

MVVM Architecture

Room Database

WorkManager

Firebase

Generative AI



---

Project Structure

Matru-Sneh-Health/
│
├── app/
├── data/
├── ui/
├── viewmodel/
├── workers/
├── screenshots/
├── README.md
└── build.gradle


---

Installation

Prerequisites

Android Studio

Android SDK

Kotlin Support


Steps

Clone the repository:

git clone https://github.com/yourusername/Matru-Sneh-Health.git

Open the project in Android Studio.

Sync Gradle dependencies.

Run the application on:

Android Emulator or

Physical Android Device



---

How to Run

Build > Run App

or press:

Shift + F10


---

Screenshots

Add screenshots inside a folder named:

screenshots/

Example:

## Home Screen

![Home](screenshots/home.png)

## Kick Counter

![Kick Counter](screenshots/kickcounter.png)


---

Future Enhancements

AI-based health recommendations

Cloud synchronization

Telemedicine integration

Voice assistance in Kannada

Health center locator

Wearable device integration



---

Social Impact

Matru-Sneh Health helps:

Improve maternal healthcare awareness

Reduce maternal health risks

Support rural healthcare digitization

Encourage timely vaccinations and check-ups



---

Internship Information

Developed during internship training at MindMatrix.


---

Author

Varun Sai V


---

License

Licensed under the MIT License. 