# Location Details Backend

This is a **Spring Boot** backend for the Location Details application. It provides APIs to fetch weather data, nearby places, and other location-based features.

## Features
1. Fetches weather details based on the user's location.
2. Retrieves nearby places categorized appropriately.
3. Supports searching for specific places and fetching related details.
4. No database is used; data is fetched dynamically from external APIs.

## Deployment
The backend is available on **GitHub**: [Location Details Backend](https://github.com/haneeth25/LocationDetailsBackend)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/haneeth25/LocationDetailsBackend.git
   ```
2. Navigate to the project folder:
   ```sh
   cd LocationDetailsBackend
   ```
3. Build the project:
   ```sh
   mvn clean install
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```
5. The server will start at:
   ```
   http://localhost:8080
   ```

## Technologies Used
- **Backend**: Spring Boot
- **Data Fetching**: External APIs (e.g., weather and location services)
- **Build Tool**: Maven

## Frontend Repository
The frontend for this project is built with **Angular** and is available on GitHub: [Location Details Frontend](https://locationdetails.netlify.app/)

## Author
Developed by [Haneeth](https://github.com/haneeth25). Feel free to contribute and raise issues!

---
