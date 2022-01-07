On MS/Windows:
o https://www.raspberrypi.com/software/
o Download imager_1.6.2.exe
o Run imager, select OS (RaspberryPi IS Full (32-bit)
o Select storage (SD card, minimum 9 GB).
o "WRITE"

Install on Rasberry
o Move the SD card to the Raspberry Pi and startup
o The SD card *is* the Raspberry Pi RAM
o Startup an answer the setup questions.
o Keep "p1/raspberry" as username/password
o Chose "Norway", but leave "English" as language

GitHub tools:
$ cd
$ mkdir Development/repos
$ cd Development/repos
$ clone https://<token>@github.com/rabbagast/tools # token from https://geosoft.no/github.txt

Emacs:
$ sudo apt-get install emacs
$ cp tools/Emacs/dotemacs ~/.emacs

tcsh:
$ sudo apt install tcsh
$ create ~/.tcshrc with single-line content: source "$DEV_HOME/tools/tcshrc"
$ in .tcshrc add
   setenv DEV_HOME $HOME/Development/repos
   setenv JAVA_HOME
   setenv IS_UNIX true

