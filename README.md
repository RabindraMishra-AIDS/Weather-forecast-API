# Weather Forecast API

This repository provides a simple Python-based interface to fetch and display current weather data for any city using the OpenWeatherMap API. It is designed as a Jupyter Notebook project and demonstrates how to interact with a public weather API, process its JSON response, and present meaningful weather statistics to users.

## Features

- Takes user input for any city name.
- Fetches current weather data from the OpenWeatherMap API.
- Displays:
  - Weather description
  - Maximum temperature (in Celsius)
  - Humidity
  - Pressure
  - Visibility
  - Wind speed
  - Country
  - Date and time of the report
- Handles invalid city names with appropriate error messages.
- Designed for interactive use in Jupyter Notebooks.

## Example Output

```
------------------------------------------------
Weather Stats for- KOLKATA||26 Apr 2023 | 06:53:12 PM
------------------------------------------------
current weather : haze
current pressure:  1006
Current Wind speed: 5.14 KMPH
Current Temperature is:31.97deg C
```

## Getting Started

### Prerequisites

- Python 3.9+
- Jupyter Notebook or JupyterLab
- An API key from [OpenWeatherMap](https://openweathermap.org/api)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/RabindraMishra-AIDS/Weather-forecast-API.git
   cd Weather-forecast-API
   ```

2. **Install required Python packages:**

   ```bash
   pip install requests
   ```

3. **Set your OpenWeatherMap API key as an environment variable:**

   You can set your API key in your OS environment before running the notebook:

   - On Linux/macOS:
     ```bash
     export rabindra=YOUR_OPENWEATHERMAP_API_KEY
     ```
   - On Windows (Command Prompt):
     ```cmd
     set rabindra=YOUR_OPENWEATHERMAP_API_KEY
     ```

## Usage

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open `weather -forecast API.ipynb` or `api-2.ipynb` in your browser.

3. Run the cells. When prompted, enter a valid city name.

4. Review the weather data displayed as output.

## Notes

- The API key is required for fetching weather data. Obtain a free key from [OpenWeatherMap](https://openweathermap.org/api) and set it as described above.
- The temperature output is converted from Kelvin to Celsius.
- The notebooks are intended for demonstration and educational purposes.


## Author

- Rabindra Mishra (AI & DS, 2023)

---

*Feel free to fork or contribute to this project!*
