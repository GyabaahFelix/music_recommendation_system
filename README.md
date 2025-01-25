# Music Recommender System

This project provides a music recommendation system that suggests similar songs based on the user's selection. The system utilizes the Spotify API to fetch album covers and uses cosine similarity to recommend similar tracks.

### Features:
-Search for a song and artist to get a list of similar tracks.
-Display album covers along with song names for recommended tracks.

### How to Run:

1.Clone this repository to your local machine.

2.Install the required dependencies by running:
pip install -r requirements.txt

3.Set up the Spotify API credentials. Create a .env file and add your CLIENT_ID and CLIENT_SECRET from Spotify:
CLIENT_ID=your_spotify_client_id

CLIENT_SECRET=your_spotify_client_secret

4. Run the app using Streamlit:
 streamlit run app.py

Enjoy using the music recommender system!
