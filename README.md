# WorkSense – Wellness Tracker  

## Overview  
**WorkSense Wellness Tracker** is a Flask-based web application designed to monitor and analyze employees’ **smoking behavior** and **stress levels**.  
It integrates with **MongoDB** for secure data storage and leverages a **logistic regression model** for stress prediction, supported by a **Deep Learning model deployed on IDS NXD Malibu**.  

The application provides real-time predictions, helping organizations promote employee well-being and better understand behavior-stress patterns.  

---

## Features  
- **User Authentication**: Secure registration and login system for personalized access.  
- **Real-time Predictions**: Continuously fetches data from an API endpoint and updates stress predictions based on smoking activity.  
- **Session Management**: Handles user sessions securely using Flask’s built-in session management.  
- **Data Storage**: MongoDB is used for storing user information and prediction history.  

---

## Installation  

1. **Clone the repository**  
   git clone https://github.com/yourusername/zeiss-wellness-tracker.git
   cd zeiss-wellness-tracker


2. **Install dependencies**
   pip install -r requirements.txt
   

3. **Run the application**
   python app.py
   

4. **Access in browser**
   Open [http://localhost:1000](http://localhost:1000)

---

## Usage

1. Register or log in to your account.
2. Monitor real-time stress predictions based on smoking behavior.
3. Log out securely after use.

---

## Technologies

* Python
* Flask
* MongoDB
* scikit-learn
* Deep Learning 

---

## Credits

Developed by **Sumukh Sudhindra Kashyap**
