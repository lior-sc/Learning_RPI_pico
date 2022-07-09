cmake_minimum_required(VERSION 3.13)

include(pico_sdk_import.cmake)

project(blink_c)

pico_sdk_init()

add_executable(blink_c
    blink.c
)

target_link_libraries(blink_c pico_stdlib)

pico_add_extra_outputs(blink_c)

