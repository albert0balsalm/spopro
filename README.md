# Spotify Listening History Analyzer

This Python script analyzes your Spotify listening history and creates visualizations based on your top tracks. Additionally, it generates seasonal playlists for your favorite genres.

## Project Structure

When you download this project, ensure that the JSON files and the Python script (`spotify_analyzer.py`) are in the same directory. The script automatically scans for JSON files and processes them without requiring explicit file path specifications.

If you encounter any issues with file access or data loading, please ensure that the JSON files are present in the same directory as the Python script.

## Prerequisites

- Python 3.x
- Spotify Developer Account (for obtaining client ID and client secret)
- Spotify account with listening history

## Getting Started

1. Clone the repository:
git clone https://github.com/your-username/spotify-listening-history.git

   
Install dependencies:

```bash
pip install spotipy pandas matplotlib seaborn


Set up Spotify API credentials:
Create a Spotify Developer Account: Spotify Developer Dashboard
Obtain your client_id and client_secret.
Set the redirect_uri in the Spotify Developer Dashboard.


Run the script:
python spotify_analyzer.py


Features
* Visualize genre distribution by time of day.
* View track counts by time of day.
* Explore the distribution of mood-related audio features.
* Check the track count by artist.
* Analyze the genre distribution of all-time tracks.
* Generate and update seasonal playlists.


Authors
Emir Musa Kibar 
emir.kibar@sabanciuniv.edu
