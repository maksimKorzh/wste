# World's Smallest Text Editor (1148 bytes)
A bare minimum terminal based text editor for Linux

# How to install it
    git clone https://github.com/maksimKorzh/wste
    cd wste
    chmod a+x e.py
    sudo cp e.py /usr/local/bin/e

# How to use it
    CONTROLS:

    Arrow keys control the cursor
    BACKSPACE deletes character or joins line
    ENTER inserts a new line or splits existing one
    Ctrl-S saves changes to the currently opened file
    Ctrl-Q quits editor

    OPEN FILE:

    e e.py      -  opens own source code
    e test.txt  -  if file "test.txt" does not exist, filename is set
    e           -  opens empty file "o.txt"

# Demonstration on YouTube
Coming soon...
