# Speedometer Web App

This web application is a simple speedometer that tracks the current speed of a person using JavaScript and the Geolocation API.

## Features

- Tracks the current speed of the user in meters per second (m/s).
- Start and stop tracking functionality.
- Responsive design.

## Technologies Used

- JavaScript: Used to handle the logic for tracking the speed and updating the UI.
- HTML: Markup language for structuring the web page.
- CSS: Styling language for designing the user interface.
- Geolocation API: Used to get the user's current location and calculate their speed.

## Usage

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Click on the "Start Tracking" button to begin tracking the speed.
4. The current speed will be displayed in meters per second (m/s), (km/hr).
5. Click on the "Stop Tracking" button to stop tracking the speed.

## How It Works

- When the "Start Tracking" button is clicked, the web app starts tracking the user's location using the Geolocation API.
- The app continuously updates the displayed speed based on the user's movement.
- The "Stop Tracking" button allows the user to stop tracking their speed.

## Known Issues

- Sometimes the speed calculation may not be accurate, especially in areas with poor GPS signals.
- Compatibility issues with older web browsers that do not support the Geolocation API.

## Preview
- Check out the live demo of the site: [Live Demo](https://speedometer-prototype.netlify.app/)

