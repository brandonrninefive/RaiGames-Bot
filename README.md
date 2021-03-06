RaiGames-Bot
===

A Python script that runs a machine learning analysis on [raigames.io](https://raigames.io/) to predict the next crash.

I used this as practice to gain some experience with supervised learning algorithms, namely K-Nearest-Neighbors. Ultimately, this was a verification of the randomness of crash results on the site. Since the crashes are fairly random in nature, which can be seen by the graph generated by this program, it was concluded that this program cannot predict future crashes very well.

This script is built with and only works with Python 3.

Installation/Usage
==

1. Install the needed dependencies with `pip install -r requirements.txt`.

2. Run the script with `python crash_fetcher.py`.

3. When prompted, enter the game hash for the game you want to use as the starting point for data collection. These hashes are publicly available on [raigames.io](https://raigames.io/).

4. View the generated graph for a plot of the crashes starting with the above game hash. To view the raw data used to
generate the plot, you can open the file `crashes.csv` which is generated by the script.
