# wxWidgets source code

## Introduction
This repository contains the source code for wxWidgets, a C++ framework for cross-platform GUI development.

## Downloading the Source Code

### Windows
1. Open a web browser and go to the wxWidgets website: https://www.wxwidgets.org/downloads/.
2. Scroll down to the "Latest stable release" section and click on the "Windows zip" link under the source code section.
3. Once the download is complete, extract the contents of the downloaded archive as a folder to the root of this folder or if you are lazy the file path is `./lib/` folder.
4. Rename the extracted folder to `wxwidgets` if you have not already.

### Linux/Mac
1. Open a terminal.
2. Install the necessary build tools (if not already installed). For example, on Ubuntu / Debian, you can run the following command:
    ```
    sudo apt-get install cmake gcc git
    ```
   For Arch / Manjaro Linux:
    ```
    sudo pacman -S cmake gcc git
    ```


3. Clone the wxWidgets repository by running the following command:
    ```
    git clone https://github.com/wxWidgets/wxWidgets.git
    ```
4. Change to the cloned repository directory:
    ```
    cd wxWidgets
    ```

## Building the Source Code

Please refer to the main README file in the root of the repository for instructions on building the framework.
