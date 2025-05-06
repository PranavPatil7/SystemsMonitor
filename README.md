# CppND-System-Monitor

I built a terminal-based system monitoring tool in C++ that replicates the functionality of 'htop', displaying real-time CPU usage, memory stats, and active process details by parsing data from the Linux /proc filesystem.

Applied object-oriented programming principles to design modular components for process management, CPU statistics, and memory monitoring, ensuring clean architecture and code reusability.

Used the ncurses library to implement a responsive, text-based user interface that updates system metrics dynamically, providing an intuitive and interactive user experience directly in the terminal.

![System Monitor](images/monitor.png)

#

## ncurses
[ncurses](https://www.gnu.org/software/ncurses/) is a library that facilitates text-based graphical output in the terminal. This project relies on ncurses for display output.




## Make
This project uses [Make](https://www.gnu.org/software/make/). The Makefile has four targets:
* `build` compiles the source code and generates an executable
* `format` applies [ClangFormat](https://clang.llvm.org/docs/ClangFormat.html) to style the source code
* `debug` compiles the source code and generates an executable, including debugging symbols
* `clean` deletes the `build/` directory, including all of the build artifacts

## Instructions

1. Clone the project repository: `git clone https://github.com/udacity/CppND-System-Monitor-Project-Updated.git`

2. Build the project: `make build`

3. Run the resulting executable: `./build/monitor`
![Starting System Monitor](images/starting_monitor.png)

5. Implement the `System`, `Process`, and `Processor` classes, as well as functions within the `LinuxParser` namespace.

6. Submit!
