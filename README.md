
# Trakt2Letterboxd
This is a simple cross-platform script to export your movies from Trakt to Letterboxd.

## What you'll need

- **Python 3.x** — if you don't have it, download and install it from the [official Python website](https://www.python.org/downloads/). The default options during installation are fine.
- The **Trakt2Letterboxd.py** file — download it from this page by clicking the green **Code** button above, then **Download ZIP**, and unzip it somewhere easy to find like your Desktop.

## How to run it

1. Open your terminal (on Mac, search for **Terminal** in Spotlight; on Windows, search for **Command Prompt**).
2. Navigate to the folder where you put the script. For example, if it's on your Desktop:
   - **Mac:** `cd ~/Desktop/Trakt2Letterboxd`
   - **Windows:** `cd %USERPROFILE%\Desktop\Trakt2Letterboxd`
3. Run the script with: `python3 Trakt2Letterboxd.py`

## Connecting your Trakt account

The first time you run the script, it will ask you to connect your Trakt account. It will print a URL and a short code, something like this:

```
Go to https://trakt.tv/activate on your web browser and enter the below user code there:

ABCD1234
```

Just open that URL in your browser, enter the code shown, and approve the connection. Come back to the terminal and the script will continue automatically.

Your login is saved locally so you won't need to do this every time.

## What you get

Two CSV files will be created in the same folder as the script:

- **trakt-exported-history.csv** — all the movies you've watched on Trakt.
- **trakt-exported-watchlist.csv** — all the movies on your Trakt watchlist.

To import them into Letterboxd, go to [letterboxd.com/import](https://letterboxd.com/import/) and upload the files there.

## Need help?

If you need more help running Python scripts, check these guides: [Windows](https://docs.python.org/3/faq/windows.html) and [MacOS](https://docs.python.org/3/using/mac.html). (Folks on Linux, you should already know what you're doing!). If nothing works, please feel free to raise a GitHub issue and I will try my best to guide you.

## Note
The script has now been updated to the new Trakt API spec (2026) and everything works as expected.