# keel

keel is a program written in Python 3 and uses ncurses to display to the user a list of
processes and their respective PIDs.

The user can easily kill the highlighted process by pressing the enter key.

This was spawned from a cyber defense hackathon in the University of Glasgow. My team
had to defend our servers and we had one terminal window open to see all open connections
and another one simply for killing. With this, we combined it into one window.

The program has/will have a way to switch the processes based on which user owns them
and will show either connections (tcp, udp, etc) as well as regular system processes.


## Dependencies
Check the requirements.txt

## How to install
keel is available on PIP! 
```bash
pip install keel
```
It is not yet available as an executable from the command line. Until then, you need to manually run the *keel.py* file with the parameters *-u* (username) and *-m* (mode). Running ```python3 keel.py -h``` will give you the help.

# Contributing
I welcome any and all contributions. Check out the issues tab to see bugs or enhancements that can be worked on.

# Contributors
[hkdeman](https://github.com/hkdeman)
[me](https://github.com/modelorona)

### Please note
The program is not fully ready. At the moment, it is under development and not everything
will work.
