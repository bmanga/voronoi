PROJECT( voronoi )
cmake_minimum_required(VERSION 2.6)
# Debug, Release, RelWithDebInfo and MinSizeRe
set(CMAKE_BUILD_TYPE RelWithDebInfo)
SET(CMAKE_VERBOSE_MAKEFILE ON)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra") # add extra warnings

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

ADD_SUBDIRECTORY(src)
