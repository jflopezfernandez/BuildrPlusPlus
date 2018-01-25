cmake_minimum_required(VERSION 3.4.3 FATAL_ERROR)
project ("new-project")

include(CheckCXXCompilerFlag)
include(CheckCXXSourceCompiles)
include(CheckIncludeFile)
include(CheckIncludeFiles)
include(CheckTypeSize)

set(SRCS src/main.cpp)

add_executable(${PROJECT_NAME} ${SRCS})
