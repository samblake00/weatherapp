# Sections 📚

✔️ Cloning the weather app\
✔️ Obtaining a valid API Key\
✔️ Running the weather app


# Clone

- The begin using the Weather app, please clone the repository into your local system using below command:
  ```bash
   git clone https://github.com/samblake00/weatherapp.git
  ```

# Obtaining a valid API Key
This application is built using tkinter and queries data from [OpenWeatherMap](openweathermap.org). In order to run the application, the user
is required to obtain a valid API key. Following the steps below to obtain a valid key and begin discovering weather data near you!

1. Sign up for an account with [OpenWeatherMap](openweathermap.org)
2. From the menu options, select API Keys
3. Generate a new API Key. Provide a key name if desired.
4. Copy and paste the generated key into weatherapp.py to start using this key and querying data.


# Running the weather app
To run the weather app, use the command below in your local terminal. 

  ```bash
  python weatherapp.py
  ```
You should see a user-interface appear immediately after running the command. It will prompt you to enter a city name. Select a city
and click "Check Weather". The response should include attributes such as temperature, pressure, humidity, clouds, and other associated information
with weather during the current time period. An example query of Denver appears as 
```
Weather of: Denver
Temperature (Celsius): 18°
Feels like in (Celsius): 18°
Pressure: 1011 hPa
Humidity: 70%
Sunrise at 05:32:49 and Sunset at 20:24:20
Cloud: 100%
Info: heavy intensity rain
```