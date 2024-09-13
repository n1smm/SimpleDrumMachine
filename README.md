# SimpleDrumMachine
A simple 2 bar drum sequencer/machine with 3 tracks/lines

## Getting it ready
It should be already functional. The only thing not inlcuded is a http-server that would allow you to run the program.
You can use whichever one you normally use for debugging (for example the server that comes with vs code).
I Normally use a vim pluging bracey (``https://github.com/turbio/bracey.vim``),
but if you dont have any of those and never did anything similar to web development and still want to see my awsome drum machine
do this (only for debian forked systems):

### Instal Nodejs
``sudo apt install nodejs``
### Install a http-server globally
``npm install -g http-server``
### Run the server
``http-server``
after that click or copy/paste the url link into your browser.
it will look sth like this (``http://127.0.0.1:8080``)

## Usage
First let it load for a couple of seconds. Then you can:

use ``space`` for play/pause

use the **slider** for adjusting the BPM of the playback

**click** in the grid to add or remove the dots. If not already at the start, it will soon be quite clear what this does.

## why and no future
So this was just a simple exploration into uderstanding the basics of p5.js library. For now i do not plan to bring this project any further since there a many many much better drum sequencers around here. A fun project that by the way I do not take credit for, since it is quite heavily based on this great tutorial series: ``https://www.youtube.com/watch?v=mmluIbsmvoY&list=PLLgJJsrdwhPywJe2TmMzYNKHdIZ3PASbr``

