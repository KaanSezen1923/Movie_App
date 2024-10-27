Here's a sample README for your project on GitHub:

---

# Movie App

This Movie App allows users to browse popular movies and search for specific films, fetching data from [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api). Built using HTML, CSS, and JavaScript, this application displays movie details dynamically, with a clean user interface and responsive design.

## Features

- **Popular Movies**: Displays a list of popular movies based on current TMDb API data.
- **Search Functionality**: Search bar allows users to look up specific movies by title.
- **Responsive Design**: Optimized for different screen sizes.
- **Hover Effects**: Displays movie details when hovering over the movie image.

## Technologies

- **Frontend**: HTML, CSS, JavaScript
- **API**: [TMDb API](https://developers.themoviedb.org/3/getting-started/introduction)
- **Styling**: Custom CSS styling for cards and thumbnails
- **Fetch API**: For retrieving and displaying movie data from the TMDb API

## Getting Started

### Prerequisites

1. **API Key**: To access the TMDb API, you’ll need to [create an account on TMDb](https://www.themoviedb.org/signup) and obtain an API key.

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/KaanSezen1923/movie_app.git
   ```
2. Open the project folder:
   ```bash
   cd movie-app
   ```

3. Add your API key in the `script.js` file:
   ```javascript
   const APILINK='https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=YOUR_API_KEY&page=1';
   const SEARCHAPI='https://api.themoviedb.org/3/search/movie?&api_key=YOUR_API_KEY&query=';
   ```

### Running the App

1. Open `index.html` in your preferred browser to view the app.

## Project Structure

- **index.html**: Main HTML file for the structure of the app.
- **style.css**: CSS file for styling the app, including layout and movie card design.
- **script.js**: JavaScript file with the main logic for fetching data and handling search functionality.

## API Endpoints

- **Popular Movies**: Fetches popular movies from TMDb:
  ```plaintext
  https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=YOUR_API_KEY&page=1
  ```
- **Search Movies**: Searches for movies by title:
  ```plaintext
  https://api.themoviedb.org/3/search/movie?&api_key=YOUR_API_KEY&query=movie_title
  ```

## Screenshots

![Ekran görüntüsü 2024-10-27 202409](https://github.com/user-attachments/assets/d4ba7f1c-736c-4221-951b-c043b01ca813)

![image](https://github.com/user-attachments/assets/608356e8-01c5-4e17-adae-3b599d65f164)


## License

This project is licensed under the MIT License.

---

Replace `YOUR_API_KEY` with your actual TMDb API key in the code sections. Feel free to add further customization and extend the functionality as needed. Enjoy building your Movie App!
