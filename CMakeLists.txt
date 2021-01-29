cmake_minimum_required(VERSION 3.10)

project(MyApp VERSION 1.0 LANGUAGES C)

add_executable(myExe main.c)

target_link_libraries(myExe PRIVATE pthread)