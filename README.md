# Spotify Clone Project

This project is a simple Spotify-like music player web application that allows users to play songs, pause, skip to the next or previous song, and see the progress of the current song.

## Features

- **Play and Pause**: Start and stop the song.
- **Next and Previous**: Skip to the next or previous song.
- **Progress Bar**: See and control the progress of the currently playing song.
- **Song List**: Display a list of songs with their cover art and names.
- **Responsive Design**: Adaptable to different screen sizes.

## Folder Structure

- `index.html`: The main HTML file that contains the structure of the website.
- `script.js`: JavaScript file containing the logic for the music player functionality, such as play/pause, next/previous, and progress bar control.
- `style.css`: CSS file to style the web page, including the layout for the navigation bar, music player interface, and responsive design.
- `logo.png`: The logo used in the navigation bar.

## Technologies Used

- **HTML**: For the structure of the web page.
- **CSS**: For styling and layout.
- **JavaScript**: For functionality such as playing/pausing songs, skipping songs, and handling the progress bar.

## How to Run

1. Download or clone this repository.
2. Open `index.html` in any web browser.
3. The music player will load with a list of available songs and their corresponding controls.

## How It Works

- The music player is initialized with an array of songs in `script.js` where each song has:
  - `songName`: The name of the song.
  - `filePath`: The path to the audio file.
  - `coverPath`: The path to the cover image.
  
- The main play button toggles between playing and pausing the current song. You can skip to the next or previous song using the corresponding buttons.
- The progress bar updates as the song plays and can also be used to skip to a specific point in the song.

## File Breakdown

### 1. `index.html`
Contains the structure of the web page, including:
- Navigation bar
- The main music player layout
- Song list with clickable play buttons

### 2. `script.js`
This file handles the music player functionality:
- Playing/pausing songs
- Displaying the song name and cover
- Skipping to the next or previous song
- Updating the progress bar as the song plays

Example of initializing song data:
```javascript
let songs = [
    {songName: "Warriyo - Mortals [NCS Release]", filePath: "songs/1.mp3", coverPath: "covers/1.jpg"},
    {songName: "Cielo - Huma-Huma", filePath: "songs/2.mp3", coverPath: "covers/2.jpg"},
    ...
];
