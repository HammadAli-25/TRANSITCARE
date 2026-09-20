# TRANSITCARE

### A Smart Platform for Reporting, Tracking & Resolving Transit Complaints

TRANSITCARE is a web-based public transport complaint management system
designed to make it easier for passengers to report, track and follow up
on problems related to public transport services.

## Features

- Passenger registration and login
- Public transport complaint submission
- Complaint tracking
- Community issue confirmation
- Live complaint statistics
- Authority dashboard
- Complaint priority and status management
- Customer-care escalation
- Automatic emergency complaint escalation
- Automatic escalation of unresolved complaints after 10 days
- Multilingual user interface
- Chatbot assistance
- Hindi and Marathi language support

## Technology Used

- Python
- Flask
- SQLite
- HTML
- CSS
- JavaScript
- Chart.js

## System Overview

TRANSITCARE has two main users:

### Passenger

Passengers can:

- Register and log in
- Submit transport complaints
- Track their complaints
- Confirm community issues
- Check complaint status
- Use the chatbot for assistance

### Transport Authority

Authorities can:

- View submitted complaints
- Update complaint priority
- Update complaint status
- Monitor complaint statistics
- View customer-care escalations
- Handle emergency complaints

## Automatic Escalation

TRANSITCARE supports two types of automatic escalation.

### Emergency Complaints

Complaints containing predefined emergency-related keywords such as
accident, injury, fire, assault, medical and danger are automatically
escalated for customer-care attention.

### Unresolved Complaints

Normal complaints that remain unresolved for 10 days or more are
automatically escalated.

Duplicate escalations are prevented for the same complaint.

## Project Structure

TRANSITCARE/
│
├── app.py
├── requirements.txt
│
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── user_home.html
│   └── authority.html
│
├── static/
│   ├── style.css
│   ├── chatbot.js
│   └── language.js
│   |__ chatbot.css
|
└── screenshots/
