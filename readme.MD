# Smart Form Submission

A lightweight, front-end–only project demonstrating a smart form built with HTML, CSS, and vanilla JavaScript.
The form includes client-side validation, dynamic UI behavior, and a clean user experience—without requiring any backend framework.

*  Features

- Pure HTML, CSS, and JavaScript
- No frameworks or build tools required.

- Smart Form Validation

- Required field checks

- Email format validation

- Real-time input feedback with debounce func


- User-Friendly UI

- Error messages and success alerts



Modular JavaScript
Logic separated into easy-to-understand functions:
validation, form handlers, and UI updates.

Project Structure
project-folder/
│
├── index.html         # Main form page
├── styles.css         # Form styling
├── app.js             # Validation + smart form logic
└── README.md          # Documentation

How to Run

Since this is a purely front-end project, no backend is required.

Option 1 — Open directly

Simply open index.html in your browser.

Option 2 — Run with a local server (recommended)

To avoid browser security limitations:

Python 3

python3 -m http.server 5500


Then visit:

http://localhost:5500/index.html

How It Works

The smart form behavior is handled entirely in app.js:

- Watches input events for validation rules

- Shows errors/warnings dynamically

- Prevents submission if fields are invalid

- Displays a success alert on completion

![Screenshot of the form](./assets/screenshot.png)

