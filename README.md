# What is it?
The EspoTek Labrador is an open-source board that converts your PC, Raspberry Pi or Android Smartphone and into a full-featured electronics lab bench, complete with oscilloscope, signal generator and more.

More information available at:
http://espotek.com/labrador

This repo hosts all of the software and hardware that makes Labrador possible.

# Documentation and Software
To download binary (executable) versions of the software, go to:

https://github.com/espotek/labrador/releases

For the documentation, please visit:

https://github.com/espotek/labrador/wiki

# Building from Source
I use Qt Creator to build the software interface.
https://www.qt.io/download-open-source/
Open Desktop_Interface/Labrador.pro, then Clean All -> Run qmake -> Build All.
If you're on Linux (including Raspberry Pi), then you can also build the software from source by cloning the repo, cd'ing to the Desktop_Interface directory then running:
```
qmake
make
sudo make install
```
Then, to launch, just type "labrador" into the terminal.

To build the AVR software, I use Atmel Studio 7.  Just load up the .atsln and push F7.  You can use avr-gcc if you don't want to install a full IDE.

The PCB files can be edited in KiCAD 4.0.

# Known bugs.
Most of the main bugs have now been fixed, including all synchronisation issues.
Please open an issue if you're aware of any in particular.

# Collaboration
If you want to make any suggestions, or better yet, submit some code, please do so here at GitHub.

Suggestions and feature requests belong on the "Issues" page.

For code submissions, look into Pull Requests.  Or you can open an issue.  I'm not picky.  :)

If you just want to say hello and remind me that people are actually using my product, please email admin@espotek.com

Thanks to all.

~Chris


# Licence
All software files are licenced under [GNU GPL v3](https://www.gnu.org/licenses/gpl.html)

All hardware files (schematics, PCB) are licenced under [Creative Commons 4.0 (CC BY-NC-SA)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
