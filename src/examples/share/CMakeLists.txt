cmake_minimum_required (VERSION 3.0)

project (dawn_slave C)

INCLUDE_DIRECTORIES(../../core)

SET(SOURCES
    ${CMAKE_CURRENT_LIST_DIR}/link.c
    )

add_executable(${PROJECT_NAME} ${SOURCES})
