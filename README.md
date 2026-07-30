# Weather Management System

A console-based Weather Management System built in **C++** using Object-Oriented Programming concepts (classes, inheritance, polymorphism). The system manages current weather data, forecasts, weather alerts, user accounts, and favourite locations — with persistent storage using file handling.

*Academic Project — OOP (C++)*

## Features

- **Current Weather** — view real-time weather info (temperature, humidity, wind speed, pressure, conditions) for saved locations
- **Weather Forecast** — day-wise forecast data for cities
- **Weather Alerts** — severity-based alert notifications for extreme weather
- **User & Admin Roles** — separate access levels for regular users and admins
- **Favourites** — save and manage favourite locations
- **System Settings** — configurable units (metric/imperial), auto-save, refresh interval
- **Persistent Storage** — weather, forecast, and user data saved to text files

## Tech Stack

- **Language:** C++
- **Concepts used:** Classes & Objects, Inheritance, Polymorphism (virtual functions), File Handling, STL (vectors)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<username>/Weather-Management-System.git
   cd Weather-Management-System
   ```
2. Compile the code:
   ```bash
   g++ main.cpp -o main
   ```
3. Run the program:
   ```bash
   ./main
   ```

> **Note:** You'll need your own OpenWeather API key to use live weather-fetching features. Add it in `main.cpp` where indicated.

## Project Structure

```
├── main.cpp              # Main source code
├── weather_data.txt      # Stored current weather data
├── forecast_data.txt     # Stored forecast data
├── system_settings.txt   # App settings
└── users.txt             # User accounts (not tracked in git)
```

## Team Members

- Esha
- Elishba
- Iman
- Khadija

## Disclaimer

This project was built for academic purposes as part of an OOP coursework assignment.
