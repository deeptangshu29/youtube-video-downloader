# Project: Youtube Video Downloader

The **Project Youtube Video Downloader** is a Windows application that allows users to download videos and audio from YouTube. The application provides a user-friendly interface and is packaged as an executable file for easy installation and usage.



### Team Members
<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/eaad8d5d-f249-4fb2-9b18-ec248d19fe1f" /></picture>

<br />
<br />

## Features
- Download videos and audio from YouTube.
- User-friendly interface for entering YouTube video URLs and selecting download options.
- Display video information such as title, author, views, and length.
- Thumbnail preview of the video.
- Select desired resolution for video downloads.
- Track download progress with a progress bar and percentage label.
- Choose destination folder for downloaded files.


<br />
<br />



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
|`os`, `threading`, `io`| for utility functions and operations|
|`pathlib`| for manipulating file paths|
|`send2trash`| for sending files to the trash instead of permanent deletion|

<br />
<br />

## Installation
To install and use the **Youtube Video Downloader** on Windows:
1. Download the executable file from the Releases.
2. Double-click the downloaded `.exe` file to start the installation process.
3. Follow the on-screen instructions to complete the installation.
4. Once installed, you can launch the application from the `Installation Location`.
   ### Installation Intruction
   - You may recieve the following warning while installing or on the first run of the application
     |<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/88f5bbc3-a121-4a51-9c3c-cb50201def85" alt="warning-page-1"></picture>|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/10ed242b-656a-4ac1-875b-051791db8eda" alt="warning-page-2"></picture>|
     |:--:|:--:|
     |Page-1|Page-2|

     > Just Click on `More Info` and then select `Run anyway`.
     > 
     > _Don't worry this is not a virus! It is a mere application developed by a group of college students who are just completing their responsibilty to complete their project_ 😅.



<br />
<br />

## Usage
1. Launch the **Project Youtube Video Downloader** application.
2. Enter the YouTube video URL in the designated field.
3. Choose between downloading the video or extracting the audio by clicking the corresponding button.
4. If downloading a video, select the desired resolution from the available options.
5. Optionally, browse and select the destination folder for downloaded files.
6. Click the "Download" button to start the download process.
7. Monitor the download progress using the progress bar and percentage label.
8. Once the download is complete, the video or audio file will be saved in the specified destination folder.
> For more detailed information check [this](#some-screenshots)

<br />
<br />

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


<br />
<br />


## Video Downloading Process

<a href="#"><img  src="https://imageupload.io/ib/iZKRXKYYtye3RbF_1690998714.gif" alt="v-min.gif"/></a>


<br />
<br />


# Some Screenshots
> Click 🖱️ or Tap 👆 for enlarged version
## Audio Downloading Process
|**Step 1**|**Step 2**|
|:--:|:--:|
|![Select Get Audio to process the link](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/da9b3567-98f7-44cb-8a4d-9b6d8288a870)|![Now Click Download to start downloading](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/54c2fa4e-b10c-42ac-bc02-20177b1ae5f8)|
|Select Get Audio to process the link|Now Click Download to start downloading|
| | |
|**Step 3**|**Step 4**|
|![Now Checking the File Size and clicking Yes to start download](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/48c8b370-b6ce-4747-96f3-96971ffee61a)|![Download has been completed successfully and is ready for streaming or sharing](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/6f6974ce-ff69-43f3-8fe8-26a9a5ab62d9)|
|Now Checking the File Size and clicking Yes to start download|Download has been completed successfully and is ready for streaming or sharing|

|Step 5|
|:--:|
|![Downloaded Audio file can be streamed](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/99790121-473e-416d-a602-ff354b1e6e77)|
|Downloaded Audio file can be streamed|


<br />
<br />
<br />
<br />


<h4 align="center">Disclaimer</h6>

- Please note that the Project: Youtube Video Downloader is specifically designed for Windows and may not be compatible with other operating systems.
- If the software is not working properly, that may occur due to a lack of maintenance or bugs in the current version of [`pytube`](https://github.com/pytube/pytube/issues).
- This is a College Project affiliated with [Maulana Abul Kalam Azad University of Technology](https://makautwb.ac.in/), West Bengal India for the subject Software Engineering


<br />
<br />

---
<p align="center">
  <i>Enjoy downloading your favorite videos and audio from YouTube with ease using the <b>Youtube Video Downloader</b>!</i>
</p>
