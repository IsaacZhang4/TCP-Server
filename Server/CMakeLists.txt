cmake_minimum_required(VERSION 3.28)
project(C_23_TCP_Client C)

set(CMAKE_C_STANDARD 23)

add_executable(C_23_TCP_Client main.c)

#Link Winsock library
target_link_libraries(C_23_TCP_Client ws2_32)