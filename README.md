# micropool-gui
Minimal Dogemone Pool

![screenshot](https://cdn.discordapp.com/attachments/515039248915628032/715245603642277928/dogemone_micropool_v1_5.PNG)



How to Guide: https://github.com/hashhound/dogemone/wiki/Dogemone-Micropool-How-to-Guide

To run micropool-gui as a nodejs/electronjs app:

    $ npm install electron -g
    $ git clone https://github.com/hashhound/micropool-gui.git
    $ cd micropool-gui
    $ npm install
    $ npm start

To build the micropool as a standalone executable:

    $ npm install electron-builder -g
    $ git clone https://github.com/hashhound/micropool-gui.git
    $ cd micropool-gui
    $ npm install
    $ electron-builder --linux
    $ electron-builder --windows
    $ electron-builder --mac
