cmake_minimum_required(VERSION 3.21)
project(KPW_Engine)

set(CMAKE_CXX_STANDARD 23)

add_executable(KPW_Engine main.cpp core/kpwengine_window.cpp core/kpwengine_window.hpp)
