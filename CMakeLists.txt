cmake_minimum_required(VERSION 3.24)
project(wechat_helper C)

set(CMAKE_C_STANDARD 11)

link_libraries(xcb xcb-util xcb-icccm)

add_executable(wechat_helper main.c)
