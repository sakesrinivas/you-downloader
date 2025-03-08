# you-downloader

![Background Image](https://raw.githubusercontent.com/sakesrinivas/you-downloader/refs/heads/main/background.png)

## Overview

YouDownloader is a Streamlit-based application that allows users to download YouTube videos in various formats. Users can choose to download the full video, crop the video to a specific time range, or extract the audio only. The app provides an easy-to-use interface for selecting download options and specifying the YouTube video URL and download path.

## Features

- **Full Video Download**: Download the entire YouTube video in the best available resolution or a specified resolution (1080p, 720p, 480p, 360p).
- **Crop Video**: Download and crop the video to a specified time range.
- **Audio Only**: Extract and download the audio from the YouTube video.

## How to Use

1. Enter the YouTube video URL in the provided text input.
2. Choose the download type from the sidebar options: Full Video, Crop Video, or Audio Only.
3. If cropping the video, specify the start and end times.
4. Click the "Download" button to start the download process.
5. The downloaded file will be saved to the specified download path.

## Requirements

- Python 3.x
- Streamlit
- yt-dlp
- moviepy
- ffmpeg
- requests

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/sakesrinivas/you-downloader.git
    cd you-downloader
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```
## Note

Please use this app for downloading videos from YouTube for fair use and educational purposes only. Respect copyright laws and the terms of service of YouTube.


## License

This project is licensed under the MIT License.