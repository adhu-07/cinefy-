# Cinefy - Your Personal Movie & Series Hub

Cinefy is a sleek, modern web application designed for movie and series enthusiasts. It offers a personalized experience, allowing users to discover, track, and get recommendations for content with a special focus on both Indian and Hollywood cinema. Built with vanilla JavaScript, it's a lightweight yet powerful single-page application that leverages multiple APIs to deliver a rich, interactive user experience.

![Cinefy App Screenshot](https://i.imgur.com/your-screenshot-url.png) 
*(Suggestion: Replace this with a real screenshot of your app!)*

---

## 🚀 Features

* **Dedicated Home Page Search:** A prominent search bar on the home page for quickly finding any movie or series.
* **Personalized Onboarding:** First-time users can select their favorite genres and film industries (Bollywood, South Indian, etc.) to tailor their content feed.
* **Blended Content Feed:** The home page intelligently mixes popular movies and web series from both India and Hollywood.
* **Dedicated Sections:**
    * **Home:** Popular movies with an integrated search bar.
    * **Web Series:** Top-rated and trending series.
    * **Anticipated:** A look at the most hyped upcoming films, separated into "Anticipated in India" and "Global Blockbusters."
    * **Upcoming:** A calendar of new theatrical releases.
* **AI-Powered Recommendations:**
    * **Mood AI:** Describe your mood and get a custom list of movie suggestions powered by the Google Gemini API.
    * **"For You" Search:** Find movies and series similar to your favorites.
* **Interactive Movie Details:**
    * **Watch Trailers:** View movie trailers directly within the app in a clean modal player.
    * **Streaming Info:** Find out where to watch a movie or series on popular Indian OTT platforms (Netflix, Prime Video, Hotstar, etc.).
* **Personal Tracking:**
    * **Watchlist:** Save titles you want to watch later. All data is saved in `localStorage`.
* **Film News:** Stay updated with the latest news from the world of cinema.
* **Fully Responsive:** A beautiful, seamless experience on desktops, tablets, and mobile devices.

---

## 🕵️‍♂️ Hidden Easter Eggs

Cinefy is filled with secrets for movie lovers to find! Try these out:

#### Search-Based Easter Eggs
Type these phrases into the "For You" or Home page search bars:

* `i am groot`
* `there is no spoon`
* `show me the money`
* `bond, james bond`
* `may the force be with you`
* `i'll be back`
* `why so serious?`
* `hakuna matata`
* `to infinity and beyond`
* `winter is coming`
* `how you doin?`
* `bazinga`
* `alohomora` (This one changes the theme!)

#### Action-Based Easter Eggs

* **Konami Code:** Type `↑ ↑ ↓ ↓ ← → ← → B A` on your keyboard for a surprise.
* **Se7en Click:** Click the "Cinefy" logo in the sidebar 7 times.

---

## 🛠️ Built With

* **Front-End:** HTML5, CSS3 (with CSS Variables for theming), Vanilla JavaScript (ES6+)
* **APIs:**
    * [**The Movie Database (TMDB)**](https://www.themoviedb.org/): For all movie/series data, posters, ratings, and recommendations.
    * [**Google Gemini**](https://ai.google.dev/): For the "Mood AI" recommendation feature.
    * [**GNews**](https://gnews.io/): For the personalized film news feed.

---

## 🏁 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You don't need any special tools or installations to run this project. A modern web browser like Google Chrome, Firefox, or Safari is all that's required.

### Installation & Setup

1.  **Clone the repository (or download the files):**
    ```sh
    git clone [https://github.com/your-username/cinefy.git](https://github.com/your-username/cinefy.git)
    ```
2.  **Get your API Keys:**
    This project requires three API keys to function correctly.
    * Create an account on [TMDB](https://www.themoviedb.org/signup) and get your API key.
    * Create an account on [Google AI Studio](https://aistudio.google.com/) to get a Gemini API key.
    * Create an account on [GNews](https://gnews.io/) to get an API key.

3.  **Add the API Keys to the project:**
    Open the `index.html` file and find the `<script>` tag at the bottom. Inside, locate the following constants and replace the placeholder text with your actual keys:

    ```javascript
    const TMDB_API_KEY = 'YOUR_TMDB_API_KEY';
    const GEMINI_API_KEY = 'YOUR_GEMINI_API_KEY';
    const GNEWS_API_KEY = 'YOUR_GNEWS_API_KEY';
    ```

4.  **Open `index.html` in your browser:**
    Simply double-click the `index.html` file, and it should open in your default web browser. That's it!

---

## 💡 Future Improvements

* **Firebase Integration:** Move user data (like the watchlist) from `localStorage` to Firestore for persistence across devices.
* **User Accounts:** Add user authentication (Email/Password or Google Sign-In) via Firebase Auth.
* **Social Features:** Implement movie reviews, user ratings, and the ability to follow other users.
