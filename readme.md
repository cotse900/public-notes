# Binary files
- [dos2unix](https://linux.die.net/man/1/dos2unix)

# Webcam
- [logitech capture](https://www.reddit.com/r/LogitechG/comments/lmlfal/how_to_add_un_supported_webcam_to_logitech_capture/)

# Markdown
[How to write markdown files](https://www.markdownguide.org/basic-syntax/)
# JS
- [JS library](https://d3js.org/)

# Compiler
- [Ubuntu compilers](https://ahelpme.com/linux/ubuntu/install-and-make-gnu-gcc-10-default-in-ubuntu-20-04-focal/)

# UNX 511 Unix System programming
- [Watler](https://mwatler.github.io/unx511_winter2021/index.html)

```sudo apt update -y
sudo apt upgrade -y
sudo apt install -y build-essential
sudo apt install -y gcc-10 g++-10 cpp-10
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-10 100 --slave /usr/bin/g++ g++ /usr/bin/g++-10 --slave /usr/bin/gcov gcov /usr/bin/gcov-10
```
# How to compile OOP345 materials locally
- [linux](https://www.cyberciti.biz/faq/howto-compile-and-run-c-cplusplus-code-in-linux/)
- install compilers like in the above section

In ubuntu, go to root folder, and then
```cd /mnt/c```
to reach c drive, for instance, and then use cd to reach the cpp file folder. For instance,
```/mnt/c/users/genig/source/repos/```
Then,
```g++ -Wall -std=c++17 -g -o ws foodorder.cpp foodorder.h w1_p1.cpp```
use the usual g++ compiling command string.
To run, for instance, "ws", just go for
```./ws```
To run additional files, go for
```./ws file1 file2...```
Valgrind is available for ubuntu and if installed, call it using
```valgrind (+compiled file)```
- [I found vgdb might block problem on 17 May](https://stackoverflow.com/questions/57206233/valgrind-showing-error-calling-pr-set-ptracer-vgdb-might-block)
- ```valgrind ./ws abc.txt whatever.file...```
