# Movie Finder App (React Native)

## 📌 Overview

Movie Finder is a mobile application built with React Native that allows users to search for movies, view detailed information, and save their favorites locally. It leverages the OMDb API to fetch real-time movie data.

## 🚀 Features

✔️ Search for movies by title through a search bar  
✔️ Retrieve movie details from the OMDb API  
✔️ Display search results with movie titles and posters in a list format  
✔️ Tap on a movie to see in-depth details, including poster, title, year, genre, and rating  
✔️ Save favorite movies locally using AsyncStorage  
✔️ Infinite scrolling to load more movies dynamically  

## 🛠️ Tech Stack

- **React Native**: For building the mobile application  
- **OMDb API**: To fetch movie data  
- **AsyncStorage**: For saving and retrieving favorite movies locally  

## ⚙️ Installation & Setup

### ✅ Prerequisites

Ensure you have the following installed:
- Node.js with npm or yarn  
- React Native CLI or Expo CLI  
- Android Studio/Xcode (for running the emulator)  
- OMDb API key (get one from [OMDb](https://www.omdbapi.com/))  

### 🔥 Running the App

1. **Clone the repository:**
                 git clone https://github.com/urvashi2711/MovieApp.git  
                 cd MovieAppUsingReactNative  
2. Install the dependencies:
                npm install
3. Set up environment variables:
                Create a .env file in the root directory and add your OMDb API key:
                     API_KEY=https://www.omdbapi.com/
4. Start the development server:
                npx react-native start
5. Run the app on an emulator or physical device:
                 For Android:
                         npx react-native run-android
                 For iOS:
                         npx react-native run-ios

📁 Folder Structure

MovieFinder/
│-- src/
│   ├── components/     # Reusable components (MovieCard, SearchBar, etc.)
│   ├── screens/        # Screens (Home, Details, Favorites)
│   ├── services/       # API handling functions
│   ├── storage/        # AsyncStorage operations
│-- assets/             # Icons and images
│-- App.js              # Main entry point
│-- package.json        # Dependencies and scripts
│-- .env                # Environment variables (API keys)

🌐 API Integration
The app fetches movie data from the OMDb API.
Example API request:
        https://www.omdbapi.com/?s=batman&apikey=your_omdb_api_key  


🔥 Future Enhancements
Add user authentication for personalized experiences
Introduce dark mode for better UI aesthetics
