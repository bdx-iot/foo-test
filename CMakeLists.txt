cmake_minimum_required(VERSION 2.6)
project(foo)
add_executable(foo foo.c)
install(TARGETS foo DESTINATION bin)
