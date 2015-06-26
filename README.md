# Titles-Youtube-Mp3

(Really bad name)

Search and download a list of videos from Youtube and convert them to mp3.


## What is Titles-Youtube-Mp3?

This is a small python script that does the following:

* Reads the file 'titles.txt', which contains a list of videos to search for
    * For example it can contain the name of a few songs you want to download and convert to mp3
    * Each line of the file is a video to search for 
* Searches Youtube via the Youtube API looking for a video matching the given keywords
    * Try to use specific keywords
    * The script just does a simple search and get the url of the first video
* Download and convert the video to mp3
    * To achieve this it uses the youtube-dl module/library 
    * The file will be placed in the same folder you started the script
    * The file will be called "{video_title}.mp3"

## How to use Titles-Youtube-Mp3?

1. Install Python 2
2. Install pip
3. Fork/Clone/Download this repository
4. Install the required packages via pip
    * pip install -r requirements.txt
5. Obtain a YouTube API key
    * Go to https://cloud.google.com/console
    * Create a new project 
    * APIs & auth > APIs > YouTube Data API > Enable API
    * Get your API key: APIs & auth > Credentials > Public API access > API key
6. Set your API key in "list2mp3.py"
    * Find DEVELOPER_KEY
    * Set DEVELOPER_KEY = {your_api_key}
7. Fill the file "titles.txt" with the videos to search and download.
    * Rememeber to use the exact video title or keywords that will get a specific video
    * One video per line
8. Run the script
    * python list2mp3.py
    * Wait
    * ???
    * Enjoy your mp3s


## Use case

This might be illegal (depending on the copyright rules of the videos) but you could use this script if you have a list of the tiles of your favourite songs (list that you generated from Pandora or Spotify for example) and you want to get the mp3s of the songs so you can listen to them on your PC or Phone.

## Need help?

If you need any help just create an Issue or send me an email at the address you can find on my profile.

## Want to help?

If you want to improve the code and submit a pull request feel free to do so.

Maybe do something to avoid the usage of the YouTube API key? 

Actually anything is accepted!

## Licensce

GPL v3







 