cmake_minimum_required(VERSION 3.18.0)

project(jenkins_test)

cmake_policy(SET CMP0057 NEW)

file (GLOB TEST_SRCS src/*.cpp)

add_executable(test ${TEST_SRCS})
