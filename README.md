# Weather App

Weather App is a Flutter application that allows users to check the weather forecast for the next five days.

## Features

- Display the current weather information for a default city.
- Allow users to dynamically change the city and see the weather forecast.
- Show a five-day weather forecast with details such as temperature, weather description, and icons.
- Provide additional information like cloud cover, pressure, humidity, and wind speed.

## Getting Started

To get started with the Weather App, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/iZeroKim/WeatherApp.git
   
2. Navigate to the project directory:

    ```bash
    cd weather-app

3. Install dependencies:

    ```bash
    flutter pub get
    
4. Run the application:

    ```bash
    flutter run

## Configuration
To configure the default city or API key, update the respective constants in the lib/constants/Constants.dart file.
    ```bash

    //lib/constants/Constants.dart
    class Constants {
      static const String API_KEY = 'your_openweathermap_api_key';
      static const String DEFAULT_CITY = 'Nairobi';
    }
##Dependencies
The Weather App relies on the following key dependencies:

http for making HTTP requests.
flutter_riverpod for state management.
intl for date formatting.

To install these dependencies, update your pubspec.yaml file:
    ```bash
    
    dependencies:
      flutter:
        sdk: flutter
      http: ^0.13.3
      flutter_riverpod: ^0.15.0
      intl: ^0.17.0

##Screenshots

![Screenshot|690x473](https://github.com/iZeroKim/WeatherApp/assets/58791465/d930adc7-b3f5-43d5-92f5-675aafe53f3e)


![Screenshot_1699816700|690x473](https://github.com/iZeroKim/WeatherApp/assets/58791465/a8168c75-ef15-46fe-b7d1-123ce183996f=100x20)



##License
This project is licensed under the MIT License.
    
