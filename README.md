# WINE-3DMark11-in-Chromebook
For enabling and benchmark gaming & gpu performance in Chrombook
# Enabling Crostini in ChromeOS
# Installing WINE5.0 for Debian buster
1) sudo dpkg --add-architecture i386
2) wget -nc https://dl.winehq.org/wine-builds/winehq.key
3) sudo apt-key add winehq.key
4) sudo vim /etc/apt/sources.list
Adding below link in sources.list
deb https://dl.winehq.org/wine-builds/debian/ buster main
deb https://download.opensuse.org/repositories/Emulators:/Wine:/Debian/Debian_10 ./
6) sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys DFA175A75104960E
7) sudo apt update
8) sudo apt install --install-recommends winehq-stable
9) winecfg
