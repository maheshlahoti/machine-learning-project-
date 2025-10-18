# 🎬 Movie Recommender Pro

An AI-powered movie recommendation system that uses content-based filtering to suggest similar movies based on plot, cast, crew, and genres.

## 🚀 Quick Start

**Clone and run the project:**


## ✨ Features

- 🎯 **Smart Recommendations**: AI-powered content-based filtering
- 🎨 **Beautiful UI**: Interactive and responsive design
- ⚡ **Fast Results**: Real-time recommendations in under 2 seconds
- 🖼️ **Movie Posters**: Integration with TMDB API for movie posters
- 📊 **Large Database**: 4,800+ movies in the database
- 🔍 **Smart Search**: Real-time movie search and filtering
- 📱 **Responsive Design**: Works on all devices

## 🚀 Live Demo

https://movie2watch-gpaedaczbhduinkn2wjtc6.streamlit.app/

**🔗 GitHub Repository**: [https://github.com/maheshlahoti/machine-learning-project-](https://github.com/maheshlahoti/machine-learning-project-)

## 🛠️ Technologies Used

- **Python 3.8+**
- **Streamlit** - Web application framework
- **Scikit-learn** - Machine learning library
- **Pandas** - Data manipulation
- **NLTK** - Natural language processing
- **TMDB API** - Movie database and posters

## 📦 Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)


## 📁 Project Structure

```
movie2watch/
├── app.py                 # Main Streamlit application
├── generate_data.py       # Data generation script
├── requirements.txt       # Python dependencies
├── procfile              # Heroku deployment configuration
├── setup.sh              # Heroku setup script
├── README.md             # Project documentation
├── .gitignore            # Git ignore file
├── tmdb_5000_movies.csv  # Movie dataset
├── tmdb_5000_credits.csv # Credits dataset
└── venv/                 # Virtual environment (not in repo)
```

## 🎯 How It Works

1. **Data Processing**: The system processes movie data including:
   - Plot summaries (overview)
   - Genres
   - Keywords
   - Cast information
   - Crew information (especially directors)

2. **Feature Engineering**: 
   - Combines all text features into a single 'tags' field
   - Applies text preprocessing (lowercasing, stemming)
   - Uses CountVectorizer to create numerical features

3. **Similarity Calculation**:
   - Computes cosine similarity between movies
   - Creates a similarity matrix for all movie pairs

4. **Recommendation Engine**:
   - Finds the 5 most similar movies for any given movie
   - Displays recommendations with movie posters
   - Provides interactive search functionality

## 📊 Dataset

The application uses the TMDB 5000 Movie Dataset which includes:
- 4,806 movies
- Movie metadata (title, overview, genres, etc.)
- Cast and crew information
- Movie posters via TMDB API

## 🔧 Configuration


## 📈 Future Enhancements

- [ ] User authentication and personalized recommendations
- [ ] Collaborative filtering integration
- [ ] Movie rating and review system
- [ ] Advanced filtering options (year, rating, etc.)
- [ ] Export recommendations functionality
- [ ] Mobile app version

---

⭐ **Star this repository if you found it helpful!**
