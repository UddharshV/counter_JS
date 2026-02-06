# Counter_JS

A simple JavaScript counter web page with three buttons: **Increase**, **Reset**, and **Decrease**. The current count is displayed in the center of the page.

## Demo / Preview
Open `index.html` in your browser and click:
- **+** to increase the count
- **RESET** to set the count back to `0`
- **-** to decrease the count

## Features
- Clean, minimal UI
- Instant counter updates using DOM manipulation
- Hover effect for buttons (CSS transition)

## Project Structure
COUNTER_JS/
- index.html
- index.js
- style.css

## How It Works
- `index.html` defines the counter label and the three buttons.
- `index.js` attaches click handlers to each button and updates the label using `textContent`.
- `style.css` centers the UI and styles the label and buttons.

## Possible Improvements

- Add min/max limits (e.g., prevent going below 0)
- Add keyboard support (↑ / ↓ / R)
- Persist count using localStorage
- Add animations for count changes
