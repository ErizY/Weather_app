Simple Weather Application
This is a simple weather application built using Django, which allows users to search for weather information by country. It integrates with the OpenWeatherMap API to provide real-time weather data.

Features
Search by Country: Users can enter the name of a country to retrieve basic weather information, including temperature, pressure, and humidity.
Real-Time Data: The application fetches weather data from the OpenWeatherMap API, ensuring that users receive up-to-date information.
User-Friendly Interface: The interface is designed to be intuitive and easy to use, making it accessible to users with varying levels of technical expertise.
Usage
Search for Weather Information:

Enter the name of the desired country in the search bar on the homepage.
Click the search button or press Enter to retrieve weather information for the specified country.
The application will display the country code, coordinates, temperature, pressure, and humidity for the selected country.
Dependencies:

Python 3.12.0
Django 5.0.3
Bootstrap (included via CDN)
Installation
Clone the repository:


git clone https://github.com/ErizY/Weather_app.git
Navigate to the project directory:

cd Weather_app
Install dependencies:


pip install -r requirements.txt
Run the Django development server:


python manage.py runserver
Access the application in your web browser at http://localhost:8000.



Cons
Limited to basic weather information; does not include advanced weather forecasts or historical data.
Relies on an external API for data, which may be subject to rate limits or downtime.
Currently lacks error handling for invalid user inputs or API responses.
Future Improvements
Implement error handling to gracefully handle invalid user inputs or API responses.
Enhance the user interface with additional features such as weather icons or interactive maps.
Integrate additional weather APIs for more comprehensive weather data coverage.
Add support for user authentication and personalized weather preferences.
License
This project is licensed under the MIT License - see the LICENSE file for details.

