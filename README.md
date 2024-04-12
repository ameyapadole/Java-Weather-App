# Weather App GUI Documentation

## Introduction

The Weather App is a Java-based application that delivers real-time weather information for any specified location. Leveraging an external API, it displays data such as temperature, weather conditions, humidity, and wind speed through a user-friendly graphical interface. This document provides a detailed overview of the project's structure, the technologies employed, and the roles of individual classes within the application.

## Technologies Employed

The Weather App incorporates several technologies and libraries, including:
- **Java 18**: The core programming language used for development.
- **[JSON Simple](https://code.google.com/archive/p/json-simple/downloads)**: A library utilized for parsing and manipulating JSON data.
- **[HTTPURLConnection](https://docs.oracle.com/en/java/javase/11/docs/api/java.net/java/net/HttpURLConnection.html)**: A Java API for making HTTP requests to obtain data from external APIs.

## Class Descriptions

### AppLauncher
**Description**: The AppLauncher is the main entry point of the Weather App. It initializes the graphical user interface and presents the main window of the application.

### WeatherAppGui
**Description**: This class is the graphical user interface of the Weather App. It is designed to display the weather details of a chosen location.
**Details**: The WeatherAppGui is tasked with arranging and displaying GUI components such as text fields, labels, buttons, and images. It provides a user interface for entering a location and updates the weather information based on user inputs.

### WeatherApp
**Description**: The WeatherApp class handles the backend logic required to fetch weather data from an external API. It obtains geographic coordinates for a location and retrieves corresponding weather data.
**Details**: As the core component of the Weather App, this class includes methods to gather weather data and geographical coordinates, translate weather codes to user-friendly descriptions, and manage API requests. It serves as a conduit between the GUI and the external data source, ensuring accurate retrieval and display of weather information.
