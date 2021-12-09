if (WIN32)
    cmake_minimum_required(VERSION 3.15)
else ()
    cmake_minimum_required(VERSION 3.13)
endif ()
set(CMAKE_CXX_STANDARD 20)
project(Template LANGUAGES CXX)

add_executable(${PROJECT_NAME} src/main.cpp)
