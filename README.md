# GameExplorer Project

[GameHub.webm](https://github.com/homayunmmdy/GameHub/assets/129702378/54abfb2a-7c20-479f-8dc4-38cf3217d878)

Welcome to GameExplorer, a dynamic game project that fetches data from the RWAG (Real World Arcade Games) API and presents it with an eye-catching UI. This project allows you to filter games by genre and platform, offers seamless ordering functionality, and even supports searching through the vast game library.

## Features

- **Data Fetching:** Utilizes RWAG API to fetch real-time game data.
- **Filtering:** Easily filter games based on genre and platform preferences.
- **Ordering:** Arrange games according to your preferences.
- **Search Functionality:** Quickly locate specific games using the search feature.
- **User Interaction:** Engage with the project by giving stars to your favorite games.

## UI Design

GameExplorer boasts an attractive user interface, ensuring a visually pleasing experience. The project incorporates beautiful loading animations to enhance user experience, even on slower internet connections.

## Prerequisites

Before getting started, make sure you have Node.js installed on your system. You can download it from [nodejs.org](https://nodejs.org/).

## Getting Started

To get started, follow these steps:

1. Clone this repository to your local machine.
2. Run `npm install` to install the required dependencies.
3. Get a RAWG API key at https://rawg.io/apidocs. You'll have to create an account first.
4. Add the API key to **src/services/api-client.ts**
5. Run `npm run dev` to start the web server.
