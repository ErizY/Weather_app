# Simple Weather Application

This is a simple weather application built using Django, which allows users to search for weather information by country. It integrates with the OpenWeatherMap API to provide real-time weather data.

## Features

- **Search by Country**: Users can enter the name of a country to retrieve basic weather information, including temperature, pressure, and humidity.
- **Real-Time Data**: The application fetches weather data from the OpenWeatherMap API, ensuring that users receive up-to-date information.
- **User-Friendly Interface**: The interface is designed to be intuitive and easy to use, making it accessible to users with varying levels of technical expertise.

## Usage

**Search for Weather Information:**

1. Enter the name of the desired country in the search bar on the homepage.
2. Click the search button or press Enter to retrieve weather information for the specified country.
3. The application will display the country code, coordinates, temperature, pressure, and humidity for the selected country.

## Dependencies

- Python 3.12.0
- Django 5.0.3
- Bootstrap (included via CDN)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ErizY/Weather_app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Weather_app
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Django development server:
    ```bash
    python manage.py runserver
    ```
5. Access the application in your web browser at http://localhost:8000.

## API Information

This application uses the OpenWeatherMap API to retrieve weather data. You can sign up for a free API key at [OpenWeatherMap](https://openweathermap.org/api) to use the API.

## Pros and Cons

### Pros

- Provides basic weather information quickly and easily.
- Real-time data ensures users receive up-to-date weather information.
- User-friendly interface makes it accessible to users of all levels.

### Cons

- Limited to basic weather information; does not include advanced weather forecasts or historical data.
- Relies on an external API for data, which may be subject to rate limits or downtime.
- Currently lacks error handling for invalid user inputs or API responses.

## Future Improvements

- Implement error handling to gracefully handle invalid user inputs or API responses.
- Enhance the user interface with additional features such as weather icons or interactive maps.
- Integrate additional weather APIs for more comprehensive weather data coverage.
- Add support for user authentication and personalized weather preferences.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
