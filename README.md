Reminder Application
Overview
This Python-based application serves as an automated reminder system utilizing the AfricasTalking API to send SMS reminders. Built with Flask, it includes a user-friendly USSD interface for inputting reminder details and an admin view for managing these reminders.

Features
USSD Interface: Allows users to interact with the service to set up medication reminders.
Admin View: Provides a web-based interface for viewing and managing scheduled reminders.
SMS Notifications: Leverages AfricasTalking SMS service to send reminders at scheduled times.
Persistence: Stores user input and reminder schedules in memory.
Input Validation: Ensures data such as dates and times are in the correct format.
Setup
Initialize AfricasTalking with your username and API key.
Run Flask app to serve the USSD callback and admin interface.
Use the BackgroundScheduler to handle the timing of reminder notifications.
Admin Usage
Access the admin dashboard at /admin to view and manage reminders. This includes deleting reminders and viewing reminder details.

Technical Details
Flask and Flask-Admin for the server and admin interface.
apscheduler for scheduling tasks.
urllib3 for AfricasTalking API interactions.
Getting Started
Run the application using Flask's built-in server and interact with the USSD interface or visit the admin page to manage reminders.
