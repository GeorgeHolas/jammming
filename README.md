# Spotify Playlist Manager

## Overview

This project is a simple Spotify playlist manager that allows users to search for songs on Spotify, add them to a playlist, and save the playlist to their Spotify account.

## Components

### `App.js`

This is the main `App` component that contains the core UI and logic for the application.

#### Functions:

- `addTrack(trackId)`: Adds a track to the playlist when the user selects it.
- `removeTrack(trackId)`: Removes a track from the playlist.
- `savePlaylist(playlistName, trackURIs)`: Saves the current playlist to the user's Spotify account.

#### Components:

- `SearchBar`: Search input to find songs on Spotify.
- `SearchResults`: Displays a list of songs returned from the search.
- `Playlist`: Displays a list of songs added to the playlist.

### `Spotify.js`

This file contains helper methods for interacting with the Spotify API.

#### Methods:

- `getAccessToken()`: Gets an access token for the Spotify API. Handles token expiration and refresh.
- `search(query)`: Searches the Spotify library for tracks based on a query term. Returns an array of track objects containing id, name, artist, album, etc.
- `savePlaylist(playlistName, trackURIs)`: Saves a playlist with a given name and list of track URIs to the user's Spotify account.

## Dependencies

- Spotify API client credentials and OAuth configuration.
- `fetch` API for making requests.

## Setup Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/spotify-playlist-manager.git
## Navigate into the project directory:
sh
Copy code
cd jammming - REACT APP
cd jammming
### Install dependencies
- npm install

### Start the development server:

- npm start
- Open the application in your browser at http://localhost:3000.
- Usage Enter a search term in the SearchBar component to search for songs on Spotify.
- View the search results in the SearchResults component and click "Add" to add a song to the playlist.
- Manage your playlist in the Playlist component by removing songs or rearranging the order.
- When you're ready, click "Save Playlist" to save your playlist to your Spotify account.
 
### Contributing
I welcome contributions! If you'd like to contribute to this project, please follow these steps:

### Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit them (git commit -am 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Create a new Pull Request.
Contact
If you have any questions or suggestions, please feel free to reach out!
