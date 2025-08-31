# ReactMovieApp
A movie web app built with React that fetches and displays trending movies from TMDB API. Users can browse popular titles, view movie details, and explore different genres through a clean and user-friendly interface

🎬 Movie Explorer
A sleek and responsive web app built with React that lets users discover trending movies and search for their favorites using the TMDB API. It features real-time search with debounce, loading indicators, and error handling for a smooth user experience
🚀 Features
🔍 Instant movie search with debounce

📈 Displays trending movies from Appwrite backend

🎞️ Movie cards with posters and titles

⏳ Loading spinner while fetching data

⚠️ Clear error messages for failed requests

🌐 Integration with TMDB API and Appwrite
🛠️ Tech Stack
React

React Hooks (useState, useEffect)

react-use for debounce

TMDB API

Appwrite (for trending movies and search analytics)

📁 Folder Structure
src/
│
├── component/
│   ├── search.jsx
│   ├── spinner.jsx
│   └── moviecard.jsx
│
├── appwrite.js         // Appwrite functions: getTrendingMovies, updateSearchCount
├── App.jsx             // Main component
└── main.jsx            // Entry point
⚙️ Setup Instructions
1-Clone the repository:
git clone https://github.com/your-username/movie-explorer.git
cd movie-explorer
2-Install dependencies:
npm install
3-Configure environment variables:
Create a .env file in the root directory and add your TMDB API key
VITE_TMDB_API_KEY=your_tmdb_api_key_here
4-Run the app:
npm run dev
🧠 Developer Notes
Debounced search reduces API calls for better performance.

Search count is updated via Appwrite when results are found.

Trending movies are fetched from Appwrite on initial load.

📸Screenshots:
<img width="1207" height="583" alt="image" src="https://github.com/user-attachments/assets/61c7d3bf-fdbf-4199-b28f-87cf1a42cb3c" />
<img width="1317" height="608" alt="image" src="https://github.com/user-attachments/assets/56f0e7c7-55ce-4431-a4bb-bfccf9eb5080" />
<img width="1271" height="573" alt="image" src="https://github.com/user-attachments/assets/b5a3db2f-3249-4e42-923b-f824cd786a49" />
📄 License
This project is open-source and free to use for educational or personal purposes.
Would you like help writing a GitHub description or setting up a deployment for this project?




