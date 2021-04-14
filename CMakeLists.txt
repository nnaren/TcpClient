cmake_minimum_required(VERSION 3.8)
Set(This TcpClient)
project(${This} CXX)

Set(Sources
    TcpClient.cpp
)

add_executable(${This} ${Sources})