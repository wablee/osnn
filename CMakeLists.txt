cmake_minimum_required (VERSION 2.8)
project (CMakeOSNN)

set (CMakeOSNN_VERSION_MAJOR 1)
set (CMakeOSNN_VERSION_MINOR 0)

add_subdirectory (src)
include_directories (src)
add_executable (CMakeOSNN osnn hello.cpp)

target_link_libraries (CMakeOSNN osnn)

install (TARGETS CMakeOSNN DESTINATION bin)
