# Project Youtube Video Downloader

The **Project Youtube Video Downloader** is a Windows application that allows users to download videos and audio from YouTube. The application provides a user-friendly interface and is packaged as an executable file for easy installation and usage.

### Team Members

|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/dd70cb8a-8d2f-44bd-90e9-d149585577ae" alt="Deeptangshu Dutta" width=100px></picture>|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/4da54fae-0e41-4393-91cb-f33de72fc036" alt="Jit Kumar Naskar" width=100px></picture>|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/fbd9c051-c36c-46cf-bda7-21138027936b" alt="Arnab Kumar Pati" width=100px></picture>|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/42dc7668-0fa8-48db-a723-bb9d5d47e0d5" alt="Snehashis Bhowmik" width=100px></picture>|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/9ca49599-d196-4b49-925b-d334ac51c00d" alt="Soumi Das" width=100px></picture>|
|:--:|:--:|:--:|:--:|:--:|
|[Deeptangshu Dutta](https://github.com/deeptangshu29)|[Jit Kumar Naskar](https://github.com/JitKrNaskar)|[Arnab Kumar Pati](https://github.com/arnab22pati)|[Snehashis Bhowmik](https://github.com/snehashis44)|[Soumi Das](https://github.com/Soumi-Das)|


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
To install and use the **Youtube Video Downloader** on Windows:
1. Download the executable file from the Releases.
2. Double-click the downloaded `.exe` file to start the installation process.
3. Follow the on-screen instructions to complete the installation.
4. Once installed, you can launch the application from the `Installation Location`.

## Usage
1. Launch the **Project Youtube Video Downloader** application.
2. Enter the YouTube video URL in the designated field.
3. Choose between downloading the video or extracting the audio by clicking the corresponding button.
4. If downloading a video, select the desired resolution from the available options.
5. Optionally, browse and select the destination folder for downloaded files.
6. Click the "Download" button to start the download process.
7. Monitor the download progress using the progress bar and percentage label.
8. Once the download is complete, the video or audio file will be saved in the specified destination folder.


## Running using Terminal
- Clone the repository from GitHub:
    ```console
    git clone "https://github.com/deeptangshu29/youtube-video-downloader.git"
    ```
- Install the required dependencies:
    ```console
    pip install -r requirements.txt
    ```
- Run the application:
    ```console
    python youtube_downloader.pyw
    ```


#### Disclaimer 
> ###### Please note that the **Project Youtube Video Downloader** is specifically designed for Windows and may not be compatible with other operating systems.
> ###### If the software is not working properly that may occur due lack of maintainance or bugs present in the current version of [`pytube`](https://github.com/pytube/pytube/issues).

---
<p align="center">
  <i>Enjoy downloading your favorite videos and audio from YouTube with ease using the <b>Youtube Video Downloader</b>!</i>
</p>
