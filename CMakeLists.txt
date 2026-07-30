cmake_minimum_required(VERSION 3.25)
include($ENV{GEODE_SDK}/share/cmake/GeodeFile.cmake)
project(NoMirrorMod)

add_geode_mod(
    ${PROJECT_NAME}
    src/main.cpp
)
