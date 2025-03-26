# Movie Search App (React Native)

## Overview

This is a Movie Search mobile application built using React Native. The app allows users to search for movies using the OMDb API, view movie details, and save their favorite movies.

## Features

✅ Search for movies by title using a search bar

✅ Fetch movie data from the OMDb API

✅ Display searched movies in a list view with names and posters

✅ Tap on a movie to view detailed information, including poster, title, year, genre, and rating

✅ Save favorite movies using AsyncStorage

✅ Load more movies at the bottom of the list

## Tech Stack
React Native: For building the mobile app

OMDb API: For fetching movie data

AsyncStorage: For storing favorite movies locally

# Installation and Setup

## Prerequisites

1. Ensure you have the following installed:
2. Node.js & npm/yarn
3. React Native CLI or Expo CLI
4. Android Studio/Xcode (for emulator)
5. An OMDb API key (get it from OMDb API)

## Steps to Run the Project

1. Clone the repository:

git clone https://github.com/Nitish4Kumar/MovieAppUsingReactNative.git
cd MovieAppUsingReactNative

2. Install dependencies:
npm install  

3. Create a .env file in the root directory and add your OMDb API key:
API_KEY=https://www.omdbapi.com/

4. Start the development server:
npx react-native start

5. Run the app on an emulator or real device:

For Android:
npx react-native run-android
For iOS:
npx react-native run-ios

## Folder Structure

MovieApp/

│-- src/

│   ├── components/   # Reusable components (MovieCard, SearchBar, etc.)

│   ├── screens/      # App screens (HomeScreen, DetailsScreen, FavoritesScreen)

│   ├── services/     # API service functions

│   ├── storage/      # AsyncStorage functions

│-- assets/           # Images and icons

│-- App.js            # Main entry point

│-- package.json      # Dependencies and scripts

│-- .env              # API keys (not to be shared)

## API Integration

The app fetches movie data from the OMDb API:
Example API request:
https://www.omdbapi.com/?s=batman&apikey=your_omdb_api_key

## Future Improvements

1. Implement user authentication
2. Add dark mode
3. Improve UI/UX design
4. Implement movie recommendations
