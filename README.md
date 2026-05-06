# 🎬 localcaption - Create offline transcripts from YouTube videos

[![](https://img.shields.io/badge/Download_localcaption-Release_Page-blue.svg)](https://github.com/Philippinesemisynthetic6617/localcaption)

## Overview 📝

localcaption turns any YouTube video into text. The program runs entirely on your computer. Your data stays on your machine. You do not need an internet connection to process the files once downloaded. You do not need paid keys or accounts with big tech companies. The tool uses reliable parts to pull the video and convert the audio into written words.

## System Requirements 💻

Your Windows computer requires the following features to run this program:

- Windows 10 or Windows 11.
- At least 8 gigabytes of RAM.
- A modern processor. 
- 5 gigabytes of free disk space for the program and the speech model.

If you have a dedicated graphics card from NVIDIA, the program runs faster. This happens because the software uses your hardware to speed up the translation of speech to text.

## 📥 Getting Started

Follow these steps to set up the software on your machine.

1. Visit the release page to download the program: [https://github.com/Philippinesemisynthetic6617/localcaption](https://github.com/Philippinesemisynthetic6617/localcaption).
2. Look for the file ending in .exe in the latest release section.
3. Save the file to your desktop or your downloads folder.
4. Double-click the file to open the program interface.

## 🛠 How to Use the Program

The interface consists of a simple window where you paste web addresses. 

1. Copy the URL of the YouTube video from your web browser.
2. Paste the URL into the input field in the localcaption window.
3. Press the Enter key on your keyboard.
4. The program downloads the audio from the video.
5. The program converts the spoken words into a transcript.
6. The status bar shows the progress of the work.
7. A text file appears in the same folder as the program once the work finishes.

## ⚙️ Understanding the Process

The tool relies on three components to work.

- yt-dlp grabs the video data from YouTube.
- ffmpeg prepares the audio for the translation engine.
- whisper.cpp turns the audio into text using machine learning models.

These tools work together in the background to ensure privacy. Because the program performs these steps on your hardware, no information travels to external servers.

## 📂 Managing Output Files

The program creates a text file for every video link you process. The file name matches the video title on YouTube. You can open these files with Notepad or any other text editor. You can copy the text to Word or Google Docs to format the content, remove grammar errors, or archive the discussions.

## 💡 Troubleshooting Common Issues

Check these items if the program stops working or fails to produce a file.

- Check your internet connection if the download part fails.
- Ensure you have enough disk space if the process stops mid-way.
- Restart the application if the window freezes.
- Make sure the URL is a direct link to the video page and not a playlist link.
- Update your Windows system to ensure compatibility with the latest features.

## 🛡 Privacy and Security

localcaption operates in a local-first mode. This means no developer collects your search history. Your transcripts exist only as files on your drive. You delete the files when you no longer need them. The software performs all calculations on your processor. It does not send audio chunks to third-party services. This setup protects your privacy.

## 🏷 Performance Expectations

The speed of the transcription depends on the length of the video and the power of your computer. A short video takes a few seconds. A long video, such as a podcast or a lecture, takes longer because the computer must process more audio data. You can watch the progress bar to see how much time remains. 

If you notice your computer is slow during the process, you can pause other heavy applications like video games or high-resolution editors. This allows the processor to dedicate its full power to the transcription task.

## 🚀 Future Updates

The project team provides updates to improve speed and quality. Check the download link periodically to see if a newer version is available. A newer version often includes faster processing times or better accuracy for identifying spoken words. You can simply replace the old .exe file with the new one to upgrade the tool.

## 💬 Frequently Asked Questions

Can I transcribe videos that are not on YouTube?
This version supports YouTube links. It focuses on the yt-dlp library to manage external web requests.

Does it support other languages?
Whisper models support many languages. The current version detects the primary language spoken in the video automatically.

What happens if the video has background music? 
The underlying model handles background noise well. It separates human speech from ambient sound to provide a clean transcript.

Do I need to install Python?
No. The provided executable file contains everything required to run the program. This makes the tool portable and simple for non-technical users. 

Where does the transcript go after it finishes?
The program saves the transcript in the same folder where you downloaded the executable file. Look for a file with the same name as the video followed by .txt.