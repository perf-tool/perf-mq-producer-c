cmake_minimum_required(VERSION 3.22)
project(perf-mq-producer-c)

set(CMAKE_CXX_STANDARD 23)
set(TARGET perf-mq-producer-c)

FILE(GLOB Sources *.h *.c)
add_executable(${TARGET} ${Sources})
