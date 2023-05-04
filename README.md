# System Monitor

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

1. Clone the project repository: `git clone https://github.com/1neskk/SystemMonitor.git`

2. Build the project: `make build`

3. Run the resulting executable: `./build/monitor`
