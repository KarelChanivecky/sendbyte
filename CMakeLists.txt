cmake_minimum_required(VERSION 3.17)
project(sendbyte C)

set(CMAKE_C_STANDARD 11)

add_executable(sendByte main.c)
target_link_libraries(sendByte pthread)

install(TARGETS sendByte DESTINATION /usr/bin)