cmake_minimum_required(VERSION 3.13)    # CMake version check
project(wx_helloworld)                  # Create project "simple_example"
set(CMAKE_CXX_STANDARD 17)              # Enable c++14 standard

add_subdirectory(lib/wxWidgets)             # Include wxWidgets

add_executable(wx_helloworld main.cpp ) # Add main.cpp file of project root directory as source file


target_link_libraries(wx_helloworld wx::net wx::core wx::base) # Link the executable to the Hello library. Hello library is added to the project via add_subdirectory command
