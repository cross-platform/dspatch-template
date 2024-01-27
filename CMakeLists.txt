cmake_minimum_required(VERSION 3.25)

project(DSPatchTemplate)

set(CMAKE_CXX_STANDARD 17)

# build dspatch

option(BUILD_STATIC "" ON)
add_subdirectory(dspatch)
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/dspatch/include)

# build app

add_executable(
    ${PROJECT_NAME}
    src/main.cpp
)

# link dspatch

target_link_libraries(
    ${PROJECT_NAME}
    DSPatch
)
