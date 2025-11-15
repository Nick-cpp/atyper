Named ASCII art typer

if you use arch by the way you can download this package from AUR ( yay -S atyper )

compilation from source code:

step 1:
you need installed gcc and git package ( Gnu Complier Collection )

$ sudo apt install gcc git - debian-based

$ sudo pacman -S gcc git - arch-based

step 2:
download the project repository

$ git clone https://github.com/Nick-cpp/atyper

step 3:
compilation & installation


$ cd atyper/

$ g++ -std=c++17 atyper.cpp -o atyper

$ sudo install -Dm755 atyper /usr/bin/atyper

step 4:
program launch

$ atyper
