# Splaylify


Splaylify is a music playlist generator built with React and Spotify API.


## Overview
------------


Splaylify allows users to search for songs, create playlists, and save them to their Spotify account.


## Installation
---------------


To install Splaylify, run the following command:

```bash
npm install
```


## Usage
-----


To start the application, run:

```bash
npm start
```


This will start the development server, and you can access the application at `http://localhost:3000`.


## Dependencies
------------


Splaylify depends on the following libraries:

* `react`: ^18.3.1
* `react-dom`: ^18.3.1
* `react-scripts`: 5.0.1
* `axios`: ^1.7.3
* `spotify-web-api`: ^1.8.0


## File Structure
----------------


The file structure for Splaylify is as follows:

* `public/`: Public assets, such as index.html and favicon.ico
* `src/`: Source code for the application
	+ `components/`: React components
		- `Track/`: Track component
		- `TrackList/`: Track list component
		- `Playlist/`: Playlist component
		- `SearchBar/`: Search bar component
		- `SearchResults/`: Search results component
	+ `util/`: Utility functions
		- `Spotify.js`: Spotify API wrapper
	+ `App.js`: Main application component
	+ `index.js`: Entry point for the application


## Contributing
------------


Contributions to Splaylify are welcome. Please fork the repository, make your changes, and submit a pull request.


## License
-------


Splaylify is licensed under the MIT License.
