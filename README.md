# Youtube to MP3/MP4 Converter

because I am sick of downloading mp3 and mp4 files from annoying websites with ads

you can either download the standalone executable: [Here](C:\Users\georg\OneDrive\Documents\GitHub\PythonMP3orMP4_YoutubeConverter\dist\main)

or download the python script: [The script](main.py) and tinker with it yourself

## Instructions
Install:

1. yt-dlp
open cmd prompt run
`pip install yt-dlp`

or if using virtual python environment:
navigate to it:
`cd: path\to\your\venv\Scripts\activate`
Then run `pip install yt-dlp`

3. ffmpeg from https://www.gyan.dev/ffmpeg/builds/
I used the version: ffmpeg-git-full.7z

Configure:
set ffmpeg path on line 25 to where ffmpeg bin folder is installed and extracted to
e.g. 'ffmpeg_location': r'C:\ffmpeg\bin'


## Running the Program
It will ask you to input:
1. URL
2. File Path then
3. mp3 or mp4 format


## Will add later
- option to select video and audio qualities
