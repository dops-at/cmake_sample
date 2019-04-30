cmake_minimum_required(VERSION 3.10)
project(hello)

set(CMAKE_INSTALL_PREFIX ${CMAKE_BINARY_DIR})

SET(CMAKE_SKIP_BUILD_RPATH  FALSE)
SET(CMAKE_BUILD_WITH_INSTALL_RPATH FALSE)
SET(CMAKE_INSTALL_RPATH "\\\$ORIGIN")
SET(CMAKE_INSTALL_RPATH_USE_LINK_PATH TRUE)

add_subdirectory(sayhello)
add_subdirectory(hello)
add_subdirectory(hello2)
