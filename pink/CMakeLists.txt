cmake_minimum_required(VERSION 3.10)
project(pink)

set(CMAKE_CXX_STANDARD 11)

include_directories(
        ${PROJECT_SOURCE_DIR}/third/slash
        /home/ligang/devspace/hogwarts/pink
)

add_executable(http_server
        ${PROJECT_SOURCE_DIR}/examples/http_server.cc
        )
