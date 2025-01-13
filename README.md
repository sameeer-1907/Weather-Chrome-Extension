# Weather-Chrome-Extension

Chrome Extension: Weather Guardian

A simple Chrome extension that provides real-time weather information based on user input. This extension helps users stay informed about the weather conditions at their desired location using the OpenWeatherMap API.

Features

User-friendly interface for entering a location.

Fetches and displays real-time weather data.

Shows temperature and weather description for the specified location.

How It Works

The user enters a location (e.g., "New York").

Upon clicking the "Get Weather" button, the extension fetches the weather data from the OpenWeatherMap API.

The weather details, including temperature and a brief description, are displayed in the extension.

Tech Stack

HTML: For creating the UI structure.

CSS: For styling the extension popup.

JavaScript: For handling user input, making API calls, and dynamically updating the UI.

Prerequisites

A valid API key from OpenWeatherMap.

Basic knowledge of Chrome extensions and JavaScript.

Getting Started

1. Clone the Repository

git clone https://github.com/amfoss/tasks.git
cd tasks/task-07

2. Create a New API Key

Sign up or log in to OpenWeatherMap.

Go to the "API Keys" section under your account.

Click + Create Key, name it, and copy the generated API key.

3. Add the API Key

Open popup.js and replace YOUR_API_KEY with your actual API key:

const apiKey = "YOUR_API_KEY"; // Replace with your OpenWeatherMap API key

4. Load the Extension in Chrome

Open Google Chrome and go to chrome://extensions/.

Enable Developer mode (top-right corner).

Click Load unpacked and select the folder containing the extension files.

The extension should now be loaded and visible in the Chrome toolbar.

5. Test the Extension

Click on the Weather Guardian icon in the toolbar.

Enter a location (e.g., "London").

Click "Get Weather" to fetch the current weather information.

Folder Structure

WeatherGuardian/
├── manifest.json      # Chrome extension manifest file
├── popup.html         # HTML file for the extension popup
├── popup.css          # CSS file for styling the popup
├── popup.js           # JavaScript file for handling API calls and UI updates
└── README.md          # Documentation file (this file)

Sample Output

If the user enters "Paris" and clicks "Get Weather", the extension might display:

Paris
Temperature: 18°C
Weather: clear sky

Troubleshooting

Common Issues

"Location not found" error:

Ensure that the location name is spelled correctly.

Make sure the API key is valid and properly inserted in popup.js.

API key not working:

Ensure your API key is active by checking it on the OpenWeatherMap dashboard.

License

This project is open-source and available under the MIT License.

Acknowledgments

OpenWeatherMap API for providing the weather data.

Chrome Extension documentation for guidance on building the extension.
