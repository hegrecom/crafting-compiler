cmake_minimum_required(VERSION 3.5)

project(machine)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(CMAKE_BINARY_DIR ${CMAKE_SOURCE_DIR}/build)
set(CMAKE_CURRENT_BINARY_DIR ${CMAKE_BINARY_DIR})
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_BINARY_DIR})

add_executable(
  machine
  Main.cpp
  Scanner.cpp
  Token.cpp
  Parser.cpp
  Generator.cpp
  Datatype.cpp
  Machine.cpp
  BuiltinFunctionTable.cpp)
