# turboc-tasm-linux
TurboC++ and TASM for Ubuntu Linux

sudo apt-get install dosbox
[https://bit.ly/2UzR7OP] Click on Download

Open Terminal and Type
$ cd ~
$ cp ~/Downloads/TURBOC-TASM.zip ~
$ unzip TURBOC-TASM.zip
$ dosbox

dosbox > mount C ~
dosbox > C:
dosbox > cd setup
dosbox > install.exe


### Change Source Drive to 'C'
### Start Installation

dosbox> config -writeconf /home/your-pc-username/dosbox.conf


Quit

open dosbox.conf which is in your home directory and type this in under [autoexec]
mount c ~
C:

Now try to open dosbox, you will see C: prompt (C drive mounted) instead of Z:

To Run Turbo C++ type
dosbox > cd ..
dosbox > cd tc/bin/
dosbox > tc.exe



