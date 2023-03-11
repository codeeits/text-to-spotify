# Text file importer

This Python script allows you to import all the songs from a text document to a Spotify playlist. Best use with apple to text or spotify to text

## Requirements
Python 3.x
spotipy 2.19.0
os

## Installation

1. Install Python 3.x on your computer.
2. Clone this repository or download the ZIP file and extract it.
3. Open a command prompt or terminal window.
4. Navigate to the directory where the repository was cloned or extracted.
5. Install the required Python modules by running the following command:
` pip install -r requirements.txt `

## Usage
1. Obtain your Spotify API credentials by following the instructions on the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).
2. Update the `client_id`, `client_secret`, `redirect_uri`, and `playlist_id` variables in the `txt-to-spotify.py` script with your own values.
3. Run the script by executing the following command:
```python text-to-spotify.py```
4. The script will prompt you to log in to your Spotify account. Follow the instructions in the command prompt or terminal window to log in.
5. The script will begin to import the song from the text file into the specified playlist.

## Running the Script on Windows
1. Open the command prompt or PowerShell terminal.
2. Navigate to the directory where the Python script is located using the `cd` command.
3. Install the required Python modules using ``pip install -r requirements.txt``.
4. Run the script using ``python text-to-spotify.py``.

## Running the Script on macOS/Linux
1. Open the terminal.
2. Navigate to the directory where the Python script is located using the ``cd`` command.
3. Install the required Python modules using ``pip install -r requirements.txt``, also try pip3 if pip doesn't work.
4. Run the script using ``python text-to-spotify.py``.

If you get a permission error while running the script on macOS/Linux, you may need to use sudo before the command to run the script as an administrator.
