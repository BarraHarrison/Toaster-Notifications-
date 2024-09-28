## Toaster Notifications Application
This project demonstrates a simple implementation of toast notifications using HTML, CSS, and JavaScript.
It provides three types of notifications: Success, Error, and Invalid Input.
Each notification is accompanied by a relevant FontAwesome icon and automatically disappears after 6 seconds.

## Features:
Success Notification: Displays a check icon and a success message.
Error Notification: Displays an 'X' icon and an error message.
Invalid Input Notification: Displays an exclamation mark icon with an invalid input message.
Notifications are styled and appear dynamically on the screen for a smooth user experience.

## Code Overview:
## HTML Structure:
The application contains three buttons to trigger different toast notifications: Success, Error, and Invalid.
An empty div with the ID toastBox is used to hold the generated toast notifications.

## JavaScript Functionality:
The showToast() function dynamically creates a toast notification and appends it to the toastBox.
Depending on the type of message, different icons and messages are displayed using FontAwesome icons.
The function checks the type of message and applies appropriate styling (for example, adding error or invalid classes).
Each notification automatically disappears after 6 seconds using setTimeout().

## External Libraries:
FontAwesome icons are used to display icons in the notifications.

This project showcases a clean and reusable implementation of toast notifications,
providing a foundation that can easily be expanded for more complex use cases.
