# Project Youtube Video Downloader

The **Project Youtube Video Downloader** is a Windows application that allows users to download videos and audio from YouTube. The application provides a user-friendly interface and is packaged as an executable file for easy installation and usage.

## Features
- Download videos and audio from YouTube.
- User-friendly interface for entering YouTube video URLs and selecting download options.
- Display video information such as title, author, views, and length.
- Thumbnail preview of the video.
- Select desired resolution for video downloads.
- Track download progress with a progress bar and percentage label.
- Choose destination folder for downloaded files.

## Technologies Used
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,py" />
  </a>
</p>

The application utilizes the following Python libraries:

|Packages|Purpose|
|:---|:---|
|`logging`|for logging purposes|
|`tkinter`| for GUI creation and user input handling|
|`urllib.request`| for opening URLs to fetch video thumbnails|
|`pytube`| for downloading YouTube videos and extracting audio|
|`PIL` _(Python Imaging Library)_| for image processing and displaying video thumbnails|
|`base64`, `os`, `threading`, `io`| for utility functions and operations|
|`pathlib`| for manipulating file paths|
|`send2trash`| for sending files to the trash instead of permanent deletion|

## Installation
To install and use the **Project Youtube Video Downloader** on Windows:
1. Download the executable file from the Releases.
2. Double-click the downloaded `.exe` file to start the installation process.
3. Follow the on-screen instructions to complete the installation.
4. Once installed, you can launch the application by double-clicking the shortcut created on your desktop or by searching for it in the Start menu.

## Usage
1. Launch the **Project Youtube Video Downloader** application.
2. Enter the YouTube video URL in the designated field.
3. Choose between downloading the video or extracting the audio by clicking the corresponding button.
4. If downloading a video, select the desired resolution from the available options.
5. Optionally, browse and select the destination folder for downloaded files.
6. Click the "Download" button to start the download process.
7. Monitor the download progress using the progress bar and percentage label.
8. Once the download is complete, the video or audio file will be saved in the specified destination folder.

Please note that the **Project Youtube Video Downloader** is specifically designed for Windows and may not be compatible with other operating systems.

Enjoy downloading your favorite videos and audio from YouTube with ease using the **Project Youtube Video Downloader**!
