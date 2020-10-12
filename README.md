# Trakt2Letterboxd
This is a simple cross-platform script to export your movies in Trakt to Letterboxd.

You require Python 3.x installed for this to run. To install Python please follow the instructions at the [official Python website](https://www.python.org/downloads/).<sup>1</sup>

To use run `python3 Trakt2Letterboxd.py` on your terminal. This will generate two csv files in the format required by Letterboxd. One titled 'trakt-exported-history.csv' (for movies you've seen) and one titled 'trakt-exported-watchlist.csv' (for movies you want to watch). You can import these files directly into the Letterboxd interface.

If you need more help running python scripts; please check these guides for your operating systems: [Windows](https://docs.python.org/3/faq/windows.html) and [MacOS](https://docs.python.org/3/using/mac.html). (Guys on Linux, you should already know what you're doing!). If you need more in-depth details please check this [guide](https://realpython.com/run-python-scripts/). If nothing works, please feel free to raise a github issue and I will try my best to guide you.

<sup>1</sup> If you want a Python2.x version, please checkout the `python2.7` branch in the repo. This branch is no longer supported.
