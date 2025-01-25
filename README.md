# Music Recommender System

This project provides a music recommendation system that suggests similar songs based on the user's selection. The system utilizes the Spotify API to fetch album covers and uses cosine similarity to recommend similar tracks.

# Link To The Dataset👇🏾
https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa3UzMFI3aWxWTzI5U3ZVSWdWRlZ0cnJHNGlpQXxBQ3Jtc0tueXMwM0xqaFhkalVLMU5iWkJHV2p3RGVyN09SZzQzZEN1dWtqemNHLWRFbFdHYUFJMFR5ZmRHR181RmNvSlpJdFpxMzZBSFhqbEl2WWVCS25EblZXdjF3TUdxOHFNZi1IaVJiX2dnb3ZIc0dsblA0UQ&q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fnotshrirang%2Fspotify-million-song-dataset&v=jm9JamrbSv8

### Features:
-Search for a song and artist to get a list of similar tracks.
-Display album covers along with song names for recommended tracks.

### How to Run:

1.Clone this repository to your local machine.

2.Install the required dependencies by running:
pip install -r requirements.txt

3.Set up the Spotify API credentials. Create a .env file and add your CLIENT_ID and CLIENT_SECRET from Spotify:
CLIENT_ID=your_spotify_client_id,
CLIENT_SECRET=your_spotify_client_secret

4. Run the app using Streamlit:
 streamlit run app.py

Enjoy using the music recommender system!
