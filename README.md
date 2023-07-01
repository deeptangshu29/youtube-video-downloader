# Project: Youtube Video Downloader

The **Project Youtube Video Downloader** is a Windows application that allows users to download videos and audio from YouTube. The application provides a user-friendly interface and is packaged as an executable file for easy installation and usage.


### Team Members

|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/dd70cb8a-8d2f-44bd-90e9-d149585577ae" alt="Deeptangshu Dutta" width=100px></picture>|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/4da54fae-0e41-4393-91cb-f33de72fc036" alt="Jit Kumar Naskar" width=100px></picture>|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/fbd9c051-c36c-46cf-bda7-21138027936b" alt="Arnab Kumar Pati" width=100px></picture>|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/42dc7668-0fa8-48db-a723-bb9d5d47e0d5" alt="Snehashis Bhowmik" width=100px></picture>|<picture><img src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/9ca49599-d196-4b49-925b-d334ac51c00d" alt="Soumi Das" width=100px></picture>|
|:--:|:--:|:--:|:--:|:--:|
|[Deeptangshu Dutta](https://github.com/deeptangshu29)|[Jit Kumar Naskar](https://github.com/JitKrNaskar)|[Arnab Kumar Pati](https://github.com/arnab22pati)|[Snehashis Bhowmik](https://github.com/snehashis44)|[Soumi Das](https://github.com/Soumi-Das)|


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
|`base64`, `os`, `threading`, `io`| for utility functions and operations|
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
> For more detailed information check [this](https://github.com/deeptangshu29/youtube-video-downloader/README.md#some-screenchots-refern_1)

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


# Some Screenchots
> Click 🖱️ or Tap 👆 for enlarged version
## Video Downloading Process
|**Step 1**|**Step 2**|
|:--:|:--:|
|![Getting Link of Desired Video from youtube.com](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/f197d548-0e03-4ca0-b348-8f9b945e0434)|![Launching the software](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/df23a8ac-288b-4369-9aec-ed418e4cb5f1)|
|Getting Link of Desired Video from youtube.com|Launching the software|
| | |
|**Step 3**|**Step 4**|
|![Pasting the YouTube Video Link Copied Earlier](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/c8c3003a-ad3e-4aef-a0c0-cc9c2ca29b5f)|![Click Get Video to process the link](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/6c5a2d2b-0c61-47ec-95e4-9ff8688038ae)|
|Pasting the YouTube Video Link Copied Earlier|Click Get Video to process the link|
| | |
|**Step 5**|**Step 6**|
|![Selecting the Preferred Resolution](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/dbba29db-cab4-41f6-9c5f-2bde560da6c8)|![Select the preferred resoltuion, for now selecting the `720p` quality](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/76fd0047-fbee-486a-9e8a-0fc6ece86921)|
|Selecting the Preferred Resolution|Select the preferred resoltuion, for now selecting the `720p` quality|
| | |
|**Step 7**|**Step 8**|
|![Click Download to Start the download proces](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/974f7715-a1f6-41b4-ab82-3143dab2a1da)|![After Clicking on Download the above pop window appears, Check the file size and to continue click on Yes](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/7da81c78-a37c-4da4-98d7-1fa1f0b3cbf1)|
|Click Download to Start the download process|After Clicking on Download the above pop window appears, Check the file size and to continue click on Yes|
| | |
|**Step 9**|**Step 10**|
|![Download process has been commenced](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/7013e152-33bb-4a5d-a579-e39bd7265d11)|![File Has Successfully been downloaded and ready to be played or shared.](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/d8f1251f-9125-4cf8-8008-063fd050b966)|
|Download process has been commenced|File Has Successfully been downloaded and ready to be played or shared.|
| | |
|**Step 11**|**Step 12**|
|![Video can be viewed successfully](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/2b7b0554-6ed5-4089-be87-c93b16759260)|![Video is being played with audio](https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/646311fa-3f1b-4ec5-aeb1-9d7085c8092e)|
|Video can be viewed successfully|Video is being played with audio|


<br />
<br />

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





<h4 align="center">Disclaimer</h6>

- Please note that the Project: Youtube Video Downloader is specifically designed for Windows and may not be compatible with other operating systems.
- If the software is not working properly that may occur due lack of maintainance or bugs present in the current version of [`pytube`](https://github.com/pytube/pytube/issues).
- This is a College Project affiliated to [Maulana Abul Kalam Azad University of Technology](https://makautwb.ac.in/), West Bengal India for the subject Software Engineering


<br />
<br />

---
<p align="center">
  <i>Enjoy downloading your favorite videos and audio from YouTube with ease using the <b>Youtube Video Downloader</b>!</i>
</p>
