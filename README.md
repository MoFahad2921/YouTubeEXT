# YouTubeEXT
- This Python script extracts comments and replies from YouTube videos and exports them to a CSV file.
- It utilizes the YouTube Data API v3 to retrieve comments and replies.

#Requirements
- Python 3.x
- Google APIs Python Client (googleapiclient)
- Pandas
- Google Colab (for running in Google Colab environment)
- A YouTube Data API key

#Usage
- Obtain a YouTube Data API key from the Google Cloud Console.
- Install the required libraries if not already installed:
- Run the script and follow the prompts to enter your YouTube API key when prompted.
- Provide the playlist IDs from which you want to extract comments.
- The script will then fetch comments and replies from all videos in the specified playlists and compile them into a CSV file.
- The CSV file will be downloaded to your local machine.

#Important Note
- Ensure that your API key has the necessary permissions to access the YouTube Data API.
