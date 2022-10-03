
# Weather App

Python was used to create the weather desktop application. This app shows weather the forecast for every days of week.



## Features

- Show the city's overall weather prediction.
- Information about the weather for the selected day.
- Determine the temperature unit (°C, °F, and K).
- Select the appropriate wind speed unit (km/h, m/s, mph, and knots).
- Keep the default values (city name, temperature unit and speed unit).
- Display default values (city name, temperature unit and speed unit).
- When starting the app, load the default values (city name, temperature unit, and speed unit).
- Display simultaneous temperature and wind speed units for the prediction for several cities.


## Technologies and sources

- Python version: 3.8
- API: weather forecast: https://openweathermap.org/forecast16
- Used icons: https://www.weatherbit.io/api/codes

## Installation and setup
Create the file 'api key.py' in the 'utils' package to utilize the application. Then add a variable called "PRIVATE API KEY" to it to hold your private API key.
Check to see if your key can get you access to this collection because this app uses Daily Forecast 16 days.


Content of: Weather-App/app/utils/api_key.py file
```python
PRIVATE_API_KEY = 'your_api_key'
```

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all essential libraries.

```bash
pip install datetime
pip install Pillow
pip install requests
```


