# GPS Location Tracker

## Overview
The **GPS Location Tracker** is a real-time location tracking web application that fetches the user's current latitude, longitude, and accuracy, and provides a direct link to view the location on Google Maps. The UI is built using Tailwind CSS for a sleek and modern design.

## Features
- **Real-Time Location Tracking**: Updates user location dynamically.
- **Google Maps Integration**: Direct link to view location on Google Maps.
- **Smooth UI**: Uses Tailwind CSS for responsive and visually appealing design.
- **Error Handling**: Displays appropriate messages if location access is denied or unavailable.

## Technologies Used
- **HTML**: Structure of the webpage.
- **CSS (Tailwind CSS)**: Styling and animations.
- **JavaScript**: Fetches geolocation and updates UI.
- **Google Maps**: Generates a direct link to the location.

## How It Works
1. On page load, the browser requests access to the user's location.
2. If access is granted, the latitude, longitude, accuracy, and timestamp are displayed.
3. A Google Maps link is generated to view the location.
4. If access is denied or unavailable, an appropriate error message is shown.

## Setup & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/gps-location-tracker.git
   ```
2. Navigate to the project folder:
   ```sh
   cd gps-location-tracker
   ```
3. Open `index.html` in a browser.
4. Grant location access when prompted.

## Author
Developed by **Eshab**. Feel free to contribute or report issues!

