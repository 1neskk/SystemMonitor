# System Monitor

This project is a system monitor similar to htop. It is a command-line tool that displays the system's CPU and memory utilization, as well as a list of processes. The project is written in C++ and uses the ncurses library to display the information in the terminal.

![image](https://user-images.githubusercontent.com/113075816/236335603-ff2f3a38-1767-4773-a704-60bb08a6b1aa.png)

## Dependencies 

Install the ncurses library within your own Linux environment: `sudo apt install libncurses5-dev libncursesw5-dev`

You also need `cmake` and `make` installed 


## Make
This project uses [Make](https://www.gnu.org/software/make/). The Makefile has four targets:
* `build` compiles the source code and generates an executable
* `format` applies [ClangFormat](https://clang.llvm.org/docs/ClangFormat.html) to style the source code
* `debug` compiles the source code and generates an executable, including debugging symbols
* `clean` deletes the `build/` directory, including all of the build artifacts

## Get Started

1. Clone the project repository

2. Build the project: `make build`

3. Run the resulting executable: `./build/monitor`
