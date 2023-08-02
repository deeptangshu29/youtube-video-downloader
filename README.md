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
<p align = "center">
<picture>
<img  src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/fc5d26ce-eb04-4428-a4a2-cb19efaf32ad" 
  alt="Installation Process"/>
</picture>
</p>


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
> For more detailed information check [this](#tutorials)

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
    python main.pyw
    ```


<br />
<br />


## Video Downloading Process
<p align = "center">
<picture>
<img  src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/2ec8dfee-f90b-4727-a245-150713db724e" 
  alt="Video Downloading Process"/>
</picture>
</p>


<br />
<br />


# Tutorials
## Audio Downloading Process
<p align = "center">
<picture>
<img  src="https://github.com/deeptangshu29/youtube-video-downloader/assets/74810289/a001cba6-9feb-4774-a88a-f642b20172e4" 
  alt="Audio Downloading Process"/>
</picture>
</p>


<br />
<br />
<br />
<br />

<pre>
<h2 align="center">Disclaimer</h2>
<ul align="center">
<li> Please note that the <b>Software: Youtube Video Downloader</b> is specifically designed for Windows 
  and may not be compatible with other operating systems but the <b>project code may or can be 
  executed in different operating systems</b> though proper working is not guaranteed. </li>
<li> If the software is not working properly, that may occur due to a lack of maintenance or bugs 
  in the current version of <a href="https://github.com/pytube/pytube/issues">pytube</a></li>
<li>This is a College Project affiliated with <a href="https://makautwb.ac.in/">Maulana Abul Kalam Azad University of Technology</a>, West Bengal India 
  for the subject Software Engineering</li>
</pre>
<ul></ul>
<br />
<br />

---
<p align="center">
  <i>Enjoy downloading your favorite videos and audio from YouTube with ease using the <b>Youtube Video Downloader</b>!</i>
</p>
