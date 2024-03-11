cmake_minimum_required(VERSION 3.25)

project(DSPatchTemplate)

set(CMAKE_CXX_STANDARD 17)

include_directories(dspatch/include)

add_executable(
    ${PROJECT_NAME}
    src/main.cpp
)
