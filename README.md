# Memory Management ChatBot

This is the project for the third course in the Udacity C++ Program: Memory Management.

The ChatBot code creates a dialogue where users can ask questions about some aspects of memory management in C++. After the knowledge base of the chatbot has been loaded from a text file, a knowledge graph representation is created in computer memory, where chatbot answers represent the graph nodes and user queries represent the graph edges. After a user query has been sent to the chatbot, the Levenshtein distance is used to identify the most probable answer. The code is fully functional as-is and uses raw pointers to represent the knowledge graph and interconnections between objects throughout the project.

## Dependencies for Running Locally
cmake >= 3.11

All OSes: click here for installation instructions

make >= 4.1 (Linux, Mac), 3.81 (Windows)

Linux: make is installed by default on most Linux distros

Mac: install Xcode command line tools to get make

Windows: Click here for installation instructions

gcc/g++ >= 5.4

Linux: gcc / g++ is installed by default on most Linux distros

Mac: same deal as make - install Xcode command line tools

Windows: recommend using MinGW

wxWidgets >= 3.0

Linux: sudo apt-get install libwxgtk3.0-gtk3-dev libwxgtk3.0-gtk3-0v5. If you are facing unmet dependency issues, refer to the official page for installing the unmet 
dependencies.

Mac: There is a homebrew installation available.

Installation instructions can be found here. Some version numbers may need to be changed in instructions to install v3.0 or greater.

## Basic Build Instructions

Clone this repo.

Make a build directory in the top level directory: mkdir build && cd build

Compile: cmake .. && make

Run it: ./membot.

