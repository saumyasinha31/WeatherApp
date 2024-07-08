
# Weather App

A simple weather app built with Flutter that uses the OpenWeatherMap API to fetch and display weather information for a given city. This app allows users to input a city name and view the current weather, including temperature, wind speed, humidity, and more.

## Features

- Get the current weather information for a specific city.
- Displays weather details like temperature, weather description, wind speed, humidity, etc.
- Shows weather icons based on the current weather condition.
- Light pink theme with a user-friendly UI.


## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- An API key from OpenWeatherMap: [Get API Key](https://home.openweathermap.org/users/sign_up)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/weather_app.git
```

2. Navigate to the project directory:

```bash
cd weather_app
```

3. Install the dependencies:

```bash
flutter pub get
```

4. Create a `consts.dart` file in the `lib` directory and add your OpenWeatherMap API key:

```dart
const String OpenWeather_API_KEY = 'your_api_key_here';
```

5. Run the app:

```bash
flutter run
```

## Usage

1. Open the app.
2. Enter the name of the city you want to get the weather information for.
3. Tap the "Get Weather" button.
4. View the weather details displayed on the screen.

## Learning Points

This app was developed as a learning project to understand how to use RESTful APIs in Flutter. Key learning points include:

- Making network requests using the `http` package.
- Parsing JSON data from the API response.
- Managing state with `setState`.
- Building a user-friendly UI with Flutter widgets.
- Handling user input with `TextField` and controllers.

## Dependencies

- [flutter](https://flutter.dev)
- [weather](https://pub.dev/packages/weather)
- [intl](https://pub.dev/packages/intl)

