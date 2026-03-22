# Interactive Weather Dashboard

A responsive web application designed to provide real-time weather analytics and 5-day forecasts. This project focuses on a clean user interface and high-performance CSS transitions to reflect current meteorological conditions.

## Live Deployment
The application is hosted via GitHub Pages and can be accessed at: 
[https://shadow-the-shadow.github.io/Weather/](https://shadow-the-shadow.github.io/Weather/)

## Technical Features
* **Real-Time Data Integration:** Utilizes the OpenWeatherMap API to fetch live atmospheric data across global coordinates.
* **Dynamic UI Transitions:** Implements a custom background layer managed by JavaScript's `requestAnimationFrame` to ensure smooth visual shifts between weather states.
* **Data Visualization:** Incorporates Chart.js to render a 5-day temperature trend line graph for easier data interpretation.
* **Persistent Search History:** Employs LocalStorage to maintain a record of the five most recent searches for optimized user experience.
* **Responsive Architecture:** Built with a glassmorphism design language, fully compatible with mobile, tablet, and desktop viewports.

## Architecture and Tools
* **Frontend:** HTML5, CSS3 (Flexbox, Pseudo-elements, CSS Variables)
* **Scripting:** JavaScript (ES6+, Fetch API, Async/Await)
* **Libraries:** Chart.js
* **API Provider:** OpenWeatherMap

## Installation and Local Execution
1.  Clone the repository to your local directory.
2.  Ensure `index.html`, `style.css`, and `script.js` are in the same root folder.
3.  Open `index.html` in a modern web browser.
4.  Input a valid city name and press 'Enter' or click 'Search' to initialize the data fetch.

---
*Developed by Lokranjan*
