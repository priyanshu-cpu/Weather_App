# Weather App (PyQt5)

A simple desktop application built with **Python** and **PyQt5** to fetch and display real-time weather information for any city. The app uses the **OpenWeatherMap API** to retrieve weather data and presents it with temperature, description, and emoji in a sleek GUI.

## Features

- Displays the current temperature in Celsius (°C) and Fahrenheit (°F).
- Shows a weather emoji based on the current weather condition.
- Displays a short description of the weather (e.g., "clear sky", "light rain").
- Simple, clean GUI with PyQt5.
- Handles errors gracefully (bad input, API issues, network problems).

## Technologies Used

- **Python 3.12**
- **PyQt5** – for GUI creation
- **Requests** – for API calls to OpenWeatherMap
- **OpenWeatherMap API** – for weather data

## Installation

### Prerequisites

Make sure Python 3.12 is installed. Check by running:

```bash
python --version
```

### Install Required Libraries

Install the required Python packages:

```bash
pip install pyqt5 requests
```

### Obtain OpenWeatherMap API Key

1. Go to [OpenWeatherMap](https://openweathermap.org/).
2. Sign up for a free account.
3. Generate an API key under the API section.
4. Replace the `api_key` variable in `Weather_App.py` with your API key.

## Running the App

1. Clone this repository:

```bash
git clone https://github.com/priyanshu-cpu/Weather_App.git
```

2. Navigate into the folder:

```bash
cd Weather_App
```

3. Run the app:

```bash
python Weather_App.py
```

4. Enter a city name and click **Get Weather** to see the current weather.

## Screenshots

![Weather App Screenshot](weather_app_ss.png)  


## Error Handling

The app handles common issues like:

- Incorrect city name
- Invalid API key
- Network connection errors
- Server issues (500, 503, etc.)

## Contributing

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## License

This project is open-source and available under the **MIT License**.
