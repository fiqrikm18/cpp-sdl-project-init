cmake_minimum_required(VERSION 3.24)
project(untitled)

set(CMAKE_CXX_STANDARD 17)

add_executable(untitled main.cpp)

target_link_libraries(
        untitled PRIVATE
        /Users/e180/SDK/cpp/SDL2.framework/Versions/A/SDL2
)

target_include_directories(
        untitled PRIVATE
        /Users/e180/SDK/cpp/SDL2.framework/Versions/A/Headers
        /Users/e180/SDK/cpp/glad/include
)