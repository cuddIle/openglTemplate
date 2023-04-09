cmake_minimum_required(VERSION 3.24)
project(opengl)

set(CMAKE_CXX_STANDARD 17)
add_executable(opengl glad.c main.cpp)
target_link_libraries(opengl GL GLU glfw3 X11 Xxf86vm Xrandr pthread Xi dl Xinerama Xcursor assimp)
