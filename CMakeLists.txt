cmake_minimum_required(VERSION 3.17)
project(imgui)

set(CMAKE_CXX_STANDARD 17)

add_library(imgui imgui.cpp imgui_demo.cpp imgui_draw.cpp imgui_tables.cpp imgui_widgets.cpp)