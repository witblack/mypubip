# what's mypubip?
A first script to get your public IP on internet. it's programmed on bash language for Linux or UNIX systems.

# How use mypub ip in Linux or Unix systems?
You can use mypubip in linux or unix systems. for use on linux systems based run command:

    - git clone https://github.com/witblack/mypubip.git
    - chmod -x mypubip.sh
    - ./mypubip.sh

NOTE:
If you have a Unix system based ( for e.g Free BSD ) you can use this script with same linux comamnds.

# How use from terminal like a command ?
Also you can move or create a link of orginal scritp for use mypubip script to use this script like a command.
So for this for follow one of meothds:

Method 1 ( Move original script ) :

    - mkdir /tmp/Installer
    - cd /tmp/Installer
    - git clone https://github.com/witblack/mypubip.git
    - #If you don't have git command install 'git' before run command. For debian based linux use 'apt-get update && apt-get install git'
    - mv mypubip/mypubip.sh /use/bin/mypubip
    - cd ~
    - rm -r /tmp/Installer
    - #Enjoy! :)

Method 2 ( Create symbolic link of original script ) ( Only advanced users * ) :

    - mkdir /tmp/Installer
    - cd /tmp/Installer
    - git clone https://github.com/witblack/mypubip.git
    - mv mypubip/mypubip.sh <location_Of_Original_Script> # replace <location_Of_Original_Script> with location you want.
    - ln -s <location_Of_Original_Script> /use/bin/mypubup # replace <location_Of_Original_Script> with same location you entered.
    - cd ~
    - rm -r /tmp/Installer

Supported Operation Systems:
-
  - Unix
  - Linux

Deepens Of Packages:
-
  - wget
  - print


Progarmmer Info:
-
Writen By WitBlack Hacker. Https://BugZone.ir/
VERSION: 1.0.0
COPY RIGHT 2023
