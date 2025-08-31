# Cineverse 🎬

### Project Objective

Cineverse is a dynamic and responsive web application for discovering movies and TV shows. The primary objective is to create a seamless user experience for browsing content, searching for specific titles, and receiving personalized recommendations. The application leverages modern web technologies to provide a fast, intuitive, and visually appealing interface that functions as a single-page application.

---

### Tools & Technologies

-   **Frontend:**
    -   **HTML5:** The core markup language used for the structure of the web page.
    -   **CSS3:** Custom styles for a dark theme and modal animations.
    -   **JavaScript (ES6+):** Powers all dynamic features, including API calls, DOM manipulation, and event handling.
    -   **Tailwind CSS:** A utility-first CSS framework for building custom, responsive designs quickly.
-   **APIs & Data:**
    -   **The Movie Database (TMDB) API:** The primary source for all movie, TV show, cast, and image data.
-   **Development Tools:**
    -   **Visual Studio Code:** The code editor used for development.
    -   **Git:** Version control system for tracking changes.

---

### API Key Source

The project uses a single API key from The Movie Database (TMDB) to fetch all its content. For simplicity and ease of use in a static project, the API key is included directly in the `index.html` file.

**Note:** For production-level applications with a backend server, it is highly recommended to use environment variables (`.env`) and keep API keys on the server side to prevent them from being publicly exposed.

---

### Key Features

-   **Comprehensive Content Display:** Features multiple content sections, including:
    -   **On-Air Movies & Shows:** Content currently in theaters or airing.
    -   **Popular Movies & Series:** Top-rated content based on audience popularity.
    -   **High-Rated Movies & Series:** Critically acclaimed films and shows.
    -   **Special Collections:** Curated lists for specific franchises like Marvel and DC, as well as movies and shows by language (Hindi, Telugu, Korean, etc.).
-   **Interactive UI:**
    -   **Infinite Horizontal Scrolling:** Navigate through content rows smoothly with dedicated scroll arrows.
    -   **Movie Detail Modal:** Clicking on a movie/show opens a modal displaying an overview, rating, genre, cast, trailers, and photo gallery.
-   **Advanced Recommendation System:**
    -   A dedicated "Get Recommendation" button opens a modal with a set of filters.
    -   Users can customize recommendations based on content type, genres, languages, production studios, minimum rating, release year, and runtime.
-   **Dynamic Search:**
    -   The search bar allows users to search the entire TMDB library.
    -   Search results are displayed in a separate, vertically scrolling grid with infinite loading.

---

### 👤 Author

-   **Author Name:** Thiruveedhula Lok Vinay
-   **GitHub:** https://github.com/LokVinay [LINK]
-   **Portfolio/Website:** https://lokvinay-portfolio.netlify.app/ [LINK]

---
