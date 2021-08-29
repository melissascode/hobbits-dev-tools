# Developing Hobbits with Visual Studio Code, Conan, and Qt Creator (on MacOS)
Visual Studio Code (VSCode) is a very popular and flexible text editor. This guide and accompanying config files should help you get set up developing hobbits with VSCode as your primary editor.

In the setup described here, Conan will be used to resolve dependencies, and Qt Creator will be used to edit Qt *.ui form files.

## Prerequisites
You should have the following tools installed:
 - A modern C++ toolchain
 - CMake 3.12+
 - Python 3.5+
 - Conan (latest version installed via pip)
 - Qt Creator
 - VSCode and its official Microsoft C++ and Python extensions

### CMake 3.12+
In the terminal, type in the command ```cmake -version``` to check whether CMake is installed. If so, the version number will appear. Instructions for installing CMake can be found [here](https://cmake.org/install/). 

### Python 3.5+

### Conan (latest version installed via pip)
In the terminal, type in the command ```conan --version``` to check whether Conan is installed. If so, the version number will appear. 

Once Python is installed, you will be able to use pip to install Conan. Type in the command ```pip install conan``` in the terminal.

Another way to install Conan is through Homebrew. If Homebrew is installed, simply type in brew install conan in the terminal. 

### Qt Creator
Click here to install Qt Creator. The version for Open Source Development will suffice for working on Hobbits.

Once VSCode and the necessary tools are successfully installed, you should watch and follow the [Hobbits Development Setup with VSCode](https://www.youtube.com/watch?v=FeOE96iISs4&t=185s&ab_channel=MahletInc) video on Youtube. The video will guide you through cloning both [Hobbits](https://github.com/Mahlet-Inc/hobbits) and [Hobbits Dev Tools](https://github.com/melissascode/hobbits-dev-tools). 
