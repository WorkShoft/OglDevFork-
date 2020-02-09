cmake_minimum_required(VERSION 2.8.4)
project(tutorial38)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(PROJECT_BINARY_DIR "dist/Debug/GNU-Linux/tutorial38")
add_custom_target(tutorial38 COMMAND make -C ${tutorial38_SOURCE_DIR}
        CLION_EXE_DIR=${PROJECT_BINARY_DIR})