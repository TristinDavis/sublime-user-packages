# My Sublime Text 2 Pakages/User folder

Link - [Sublime Text 2](http://www.sublimetext.com/)

Installing:

    $ cd %APPDATA%\Sublime Text 2\Packages # Windows
    $ cd ~/.config/sublime-text-2/Packages # Linux
    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages # Mac OS X
    $ git clone git@github.com:asux/sublime-user-packages.git User
    $ cd User
    $ git modules init
    $ git modules update
    $ cd ..
    $ ln  -s 'User/Theme - Soda' . # theme should be in Packages folder

Update:
  
    $ cd /path/to/User
    $ git pull
    $ git submodules update