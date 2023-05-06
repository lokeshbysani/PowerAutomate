# Event Registrations and Confirmations automated with Power Automate Cloud Flow!

### Summary
Automate event registration and confirmation emails with Google Forms, Sheets, and Power Automate. 

This Project performs below actions:

* Users submit responses in Microsoft forms is captured by Power Automate cloud flow. 
* Google Forms are submitted by users, and the responses are automatically stored in Google Sheets.
* A Google Apps Script fetches the data related to each day, and only the rows relevant to that data are retrieved in another sheet.
* Power Automate reads the data in that sheet and sends confirmation emails to the users, adding them to the event.

### Architecture Diagram

![Technical Design](/Assets/)

### Tools used
Power Automate Cloud flow,Google forms,Google Apps Script,Google Sheets,Outlook.

### Benefits
* **Saves time**: The entire workflow is automated, freeing upto **5 hours** of time per week that would have been spent manually managing event registrations and sending confirmation emails.
* **Reduces errors**: Automation reduces the likelihood of human error, resulting in more accurate event registration and confirmation processes.
* **Enhances attendee experience**: Attendees receive confirmation emails quickly and are added to the event promptly, creating a positive experience for them.
* **Improves planning process**: The automated process simplifies event management, providing organizers with more time to focus on planning and executing the event.

### Flow

![Technical Design](/Assets/)
