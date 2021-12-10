# My learning journey

## [funny-fun-time](https://github.com/StephenAppleby/funny-fun-time)
My first Python script. After working my way through the [official Python tutorial](https://docs.python.org/3/tutorial/), I decided to consolodiate my understanding with this very simple script.

Using the requests module, it fetches a dad joke from icanhazdadjoke.com then prints one joke per line every 8 seconds indefinitely. If the user attempts to exit, the script catches the KeyboardInterrupt, halves the delay between jokes and continues. Crude but fun

Skills/tools:
- Python fundamentals
- The basics of the requests library
- Basic exception handling

### bomfc
The Beureau Of Meteriology ForeCast script was a simple tool I made for myself to print the weather to the terminal for me every morning.

The first step is to extract the xml file from the BOM FTP server using the ftplib module. Then the xml is parsed using the xml.etree.ElementTree class and extracting the desired information. This information is then formatted and printed to the console. Simple but useful

Skills/tools:
- ftplib
- xml parsing basics
- string formatting

### vidman
Another personal project to help me manage my video downloads. vidman is a wrapper for youtube-dl and aria2c.

Using the argparse module, I created an interface with several subparsers for commands for adding, editing and deleting Youtube playlists, loading videos with youtube-dl until the playlist folder is full, loading all playlists and deleting videos when watched. It was a great exercise in consolidating my basic Python skills as well as gaining a comfortable familiarity with json parsing and the pathlib module. I use it every day

Skills/tools:
- pathlib
- json parsing
- basic subprocess usage
- argparse

## Data structures and algorithms
