cmake_minimum_required(VERSION 3.1...3.15)

if(${CMAKE_VERSION} VERSION_LESS 3.12)
  cmake_policy(VERSION ${CMAKE_MAJOR_VERSION}.${CMAKE_MINOR_VERSION})
endif()

project(examples LANGUAGES CXX)

add_subdirectory(basic)

add_subdirectory(cpp11)

add_subdirectory(cpp17)
