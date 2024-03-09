cmake_minimum_required(VERSION 3.13)    # CMake version check
project(wx_helloworld)                  # Project Name
set(CMAKE_CXX_STANDARD 17)              # Enable c++17 standard

add_subdirectory(lib/wxWidgets)         # Include wxWidgets as a subdirectory

add_executable(${PROJECT_NAME} 

    main.cpp 

) # Add executable target with source files listed in the file GLOB

target_link_libraries(${PROJECT_NAME} wx::base wx::core wx::net wx::ribbon wx::richtext wx::stc wx::xml wx::qa wx::gl wx::html wx::adv wx::aui wx::propgrid wx::xrc wx::gl wx::media) # Link the target to the wxWidgets libraries