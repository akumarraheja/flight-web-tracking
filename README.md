### Flight Tracker Web App

Requirement:
- To save as much time as possible to take the flight on time.
- If the flight is delayed, the user can leave late, however if the flight is on time, the user must leave on time.

Project Overview:
- The purpose of this project is to create a web application that allows users to enter a flight number, retrieve relevant flight details including departure airport information, and calculate the optimal time to leave their current location to arrive at the airport on time. This application will integrate external APIs for flight information and Google Maps API.

User Interface
- Home Page: A simple interface where the user can input the flight number and the date.
- Flight Information Display:
  - Once the flight number is submitted, the app will display detailed flight information.
  - The display should include:
      - Flight Number
      - Airline Name
      - Departure Airport (with location details)
      - Departure Gate and Terminal
      - Departure Time
      - Arrival Airport
      - Arrival Time
      - Flight Status (if available)
- Recent Searches: A section where the user can view their recent flight searches.

Flight Information Retrieval
- API Integration:
  - The app will trigger an API call to fetch the flight details after the user enters the flight number.
  - The API should return all relevant details, including the departure airport, gate, terminal, and flight status.

Travel Time Calculation
- Google Maps API Integration:
  - After retrieving the flight details, the app will calculate the estimated travel time from the user’s current location to the departure airport using the Google Maps API.
  - The app should also consider the user’s mode of transportation (car, public transit, walking, etc.).
  - Display the recommended departure time to leave for the airport, considering factors such as traffic.


Data Persistence
- Database Integration:
  - Save the user's recent flight searches along with the retrieved flight data into the database

Additional Information Display
- Display any additional information available from the flight API, such as:
  - Any delays or cancellations

Please find below some example screenshots:

![image](https://github.com/user-attachments/assets/1c930c10-b82d-4c83-b6de-368b96b2b45b)
![image](https://github.com/user-attachments/assets/11640ad0-f96e-453b-88c9-5f7d4f282c6b)
![image](https://github.com/user-attachments/assets/3da3993d-3530-4842-8819-8879b502ed3f)

