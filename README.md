# 🎬 BingeYourMood

BingeYourMood is a simple and responsive movie search web application that allows users to search for movies, TV series, and episodes using the OMDb API. The project demonstrates the use of modern JavaScript concepts such as **Fetch API**, **Async/Await**, **Debouncing**, and **DOM Manipulation**.

## 🚀 Features

* 🔍 Search movies by title
* 🎥 Filter results by:

  * Movie
  * Series
  * Episode
* 📅 Optional year-based filtering
* ⚡ Real-time search with debounce optimization
* 📄 Pagination support for navigating search results
* 🖼️ Movie posters with fallback image support
* 🔗 Direct navigation to IMDb pages
* 📱 Responsive and modern user interface
* 🚨 Error handling for failed requests and empty results

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* Fetch API
* Async/Await
* OMDb API

## 📂 Project Structure

```text
BingeYourMood/
│
├── index.html      # Main HTML structure
├── styles.css      # Styling and responsive design
├── script.js       # Application logic and API integration
└── README.md       # Project documentation
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/BingeYourMood.git
```

### 2. Navigate to the Project Folder

```bash
cd BingeYourMood
```

### 3. Open the Project

Simply open the `index.html` file in your browser.

## 🔑 OMDb API Configuration

This project uses the OMDb API.

1. Visit: https://www.omdbapi.com/apikey.aspx
2. Generate your API key.
3. Replace the API key in `script.js`:

```javascript
const API_KEY = 'YOUR_API_KEY';
```

## 📖 How It Works

1. User enters a movie title.
2. Optional filters (type and year) can be applied.
3. JavaScript sends an API request using the Fetch API.
4. Results are displayed dynamically as movie cards.
5. Users can navigate through pages using Previous and Next buttons.
6. Clicking a movie card opens its IMDb page in a new tab.

## 🧠 Concepts Demonstrated

* Asynchronous Programming
* API Integration
* Fetch API
* Async/Await
* Debouncing
* Event Handling
* DOM Manipulation
* Responsive Web Design
* Pagination Logic
* Error Handling

## 📸 Sample Use Cases

* Search for movies like "The Matrix"
* Browse TV series
* Find content released in a specific year
* Explore IMDb details directly

## 🔮 Future Enhancements

* Movie details modal
* Favorites/Watchlist feature
* Dark/Light mode toggle
* Genre filtering
* Infinite scrolling
* Local storage support

## 👨‍💻 Author

**Kritansh Pandey**

B.Tech (CSE) Student
IIMT University, Greater Noida

## 📜 License

This project is developed for educational and learning purposes.
