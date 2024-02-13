                            Omar Marzhan Assignment 3
My theme is cities. This project is a web application that provides various services related to information about cities, weather, and time.
It uses the following APIs:
1. Pexels API: for getting photos of cities.
2. OpenWeatherMap API: To get weather information for a specific city.
3. TimezoneDB API: To get the current time in different time zones.
4. GeoNames API: To get information about cities such as name, country and population.

                 The application supports the following features:

- User Registration and Authentication: Users can register, authenticate and log in to access various features.
- User management: Administrators have the ability to view, edit and delete users.
- Getting information about cities: Users can get information about various cities such as weather, photos and general information about cities.
- Query History: The app stores user query history, including queries to various APIs and their results.

 
      The following technologies and tools were used to develop the application:

- Node.js and Express.js: to create the backend of the application.
- MongoDB and Mongoose: for storing user data, weather, time, photos and query history.
- bcryptjs: for hashing user passwords before storing and comparing hashes during authentication.
- Axios: For making HTTP requests to external APIs.
- dotenv: to load configuration from .env file.
- ejs: for creating and displaying HTML templates.
- body-parser: for processing form data in requests.

                          Installation and launch
Clone the repository to your computer.
Install the dependencies by running npm install.
Create a .env file in the project's root directory and add the necessary environment variables.
Run the application in the terminal of the "node server.js" project folder.
You can then open the application in your browser at http://localhost:3000.