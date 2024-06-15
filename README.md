
# Weather App

## Overview

The Weather App is a simple, user-friendly web application that provides real-time weather updates for any city. It displays temperature, humidity, wind speed, and weather conditions using visually appealing icons.

## Developed By

- Suhaas Nv

## Features

- Real-time weather updates for any city
- Displays temperature, humidity, wind speed, and weather conditions
- Visually appealing icons for different weather conditions
- Responsive design

## Prerequisites

Before running the Weather App, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm) (Node Package Manager)

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. **Install Dependencies**

    Run the following command to install all necessary dependencies:

    ```bash
    npm install
    ```

3. **API Key Setup**

    - Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api).
    - Create a `.env` file in the root directory of the project.
    - Add the following line to the `.env` file, replacing `YOUR_API_KEY` with your actual OpenWeatherMap API key:

      ```bash
      VITE_APP_ID=YOUR_API_KEY
      ```

## Running the Application

To start the application, run:

```bash
npm run dev
```

Open your web browser and navigate to `http://localhost:3000` to see the Weather App in action.

## Usage

1. **Search for a City**

    - Enter the name of the city in the search bar.
    - Press the `Enter` key or click the search icon to get the weather updates.

2. **View Weather Details**

    - The app will display the current temperature, weather condition, humidity, and wind speed for the entered city.

## Icons

The app uses various icons to represent different weather conditions. Ensure you have the following image files in the `assets` directory:

- `search.png`
- `clear.png`
- `cloud.png`
- `drizzle.png`
- `rain.png`
- `snow.png`
- `wind.png`
- `humidity.png`

## License

This project is licensed under the MIT License.

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for the weather API
- [React](https://reactjs.org/) for the frontend framework
- [Poppins](https://fonts.google.com/specimen/Poppins) for the font
- [CSS Gradient](https://cssgradient.io/) for the background gradient

For any issues or contributions, please feel free to open an issue or pull request on the GitHub repository.

---

Thank you for using the Weather App!
