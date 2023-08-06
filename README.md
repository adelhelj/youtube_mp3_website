# YouTube MP3 Website

YouTube MP3 Website is a simple web application built with Flask that allows users to download the audio from YouTube videos in MP3 format.

<p align="center">
  <img src="https://github.com/adelhelj/youtube_mp3_website/blob/main/youtube_mp3_website.png" width="65%">
</p>

## Features

- Download audio from YouTube videos in MP3 format.
- Cool techy theme for a modern look and feel.

## Requirements

- Python 3.6 or higher
- Flask
- pytube

## Installation

1. Clone this repository to your local machine.
2. Install the required packages by running the following command:

   ```
   pip install Flask pytube
   ```

## Usage

1. Run the Flask app by executing the `app.py` file:

   ```
   python app.py
   ```

2. Open your web browser and go to `http://localhost:5000`.

3. You will be greeted with the YouTube Audio Downloader website.

4. Enter the URL of the YouTube video you want to download the audio from.

5. Click the "Download Audio" button, and the MP3 audio file will be downloaded to your local machine.

## Folder Structure

```
youtube_mp3_website/
│   app.py
│   requirements.txt
│
├── static/
│   └── styles.css
│
└── templates/
    └── index.html
```

## Deployment

You can deploy this app to a cloud platform such as Heroku or PythonAnywhere for free. Follow their respective documentation to deploy the Flask app.

## Disclaimer

This application is intended for personal use only. Please respect copyright laws and use the downloaded audio files responsibly.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the developers of Flask and pytube for providing the tools to build this application.
