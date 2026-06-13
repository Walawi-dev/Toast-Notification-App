# Toast Notification App

A small demo web app showing how to create animated toast notifications using plain HTML, CSS, and JavaScript.

## Overview

This project provides a simple UI for displaying three types of toast notifications:

- **Success**
- **Error**
- **Invalid**

Each notification slides in from the right, stays visible for a short duration, and disappears automatically.

## Files

- `index.html` — main page with buttons and inline JavaScript for triggering notifications.
- `style.css` — styling for the page layout, toast animations, and notification appearance.

## Features

- Animated toast slide-in effect
- Automatic dismissal after 6 seconds
- Different styles for success, error, and invalid alerts
- Font Awesome icons used for notification visuals

## Usage

1. Open `index.html` in a browser.
2. Click one of the buttons:
   - `Success`
   - `Error`
   - `Invalid`
3. A toast notification appears in the lower-right corner.

## Customization

- Update the message text in `index.html` by editing `successMsg`, `errorMsg`, and `invalidMsg`.
- Change the duration by modifying the `setTimeout` delay in the `showToast` function.
- Adjust colors, animation timing, or toast size in `style.css`.

## How it works

- When a button is clicked, `showToast(msg)` creates a new `div` element with class `toast`.
- The notification content is inserted using `innerHTML`.
- Conditional classes (`error`, `invalid`) are added based on the message text.
- The toast is removed from the DOM after 6000ms.

## Notes

- This example is intentionally lightweight and does not use any build tools.
- For production use, consider separating JavaScript into its own file and improving accessibility.

## License

This repository is provided as-is for learning and demonstration purposes.
