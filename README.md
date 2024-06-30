Movie Recommender System
This project is a web-based application that recommends movies to users based on their preferences. It uses collaborative filtering and cosine similarity on movie metadata to generate recommendations.

Features
Recommends movies based on user input
Displays movie posters fetched using The Movie Database (TMDb) API
User-friendly interface built with Streamlit
Installation
Clone the repository:
sh
Copy code
git clone https://github.com/yourusername/movie-recommender-system.git
Navigate to the project directory:
sh
Copy code
cd movie-recommender-system
Create a virtual environment and activate it:
sh
Copy code
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
Install the required packages:
sh
Copy code
pip install -r requirements.txt
Set up the TMDb API key:
Create a file named .env in the root directory of the project.
Add the following line to the .env file, replacing YOUR_API_KEY with your actual TMDb API key:
makefile
Copy code
TMDB_API_KEY=YOUR_API_KEY
Usage
Run the application:
sh
Copy code
streamlit run app.py
Open your web browser and go to http://localhost:8501.
Project Structure
app.py: The main application file
model.py: Contains the recommendation model
requirements.txt: List of required Python packages
README.md: This file
How It Works
The application uses a dataset of movies and their metadata to recommend movies based on user input. The recommendation is generated using cosine similarity, which measures the similarity between the metadata of different movies.
