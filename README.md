

# Movie Recommender System

This project is a web-based application that recommends movies to users based on their preferences. It uses collaborative filtering and cosine similarity on movie metadata to generate recommendations.

## Features

- Recommends movies based on user input
- Displays movie posters fetched using The Movie Database (TMDb) API
- User-friendly interface built with Streamlit

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/movie-recommender-system.git
   ```
2. Navigate to the project directory:
   ```sh
   cd movie-recommender-system
   ```
3. Create a virtual environment and activate it:
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```
4. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```
5. Set up the TMDb API key:
   - Create a file named `.env` in the root directory of the project.
   - Add the following line to the `.env` file, replacing `YOUR_API_KEY` with your actual TMDb API key:
     ```
     TMDB_API_KEY=YOUR_API_KEY
     ```

## Usage

1. Run the application:
   ```sh
   streamlit run app.py
   ```
2. Open your web browser and go to `http://localhost:8501`.

## Project Structure

- `app.py`: The main application file
- `model.py`: Contains the recommendation model
- `requirements.txt`: List of required Python packages
- `README.md`: This file

## How It Works

The application uses a dataset of movies and their metadata to recommend movies based on user input. The recommendation is generated using cosine similarity, which measures the similarity between the metadata of different movies.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

