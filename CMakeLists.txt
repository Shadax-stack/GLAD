cmake_minimum_required(VERSION 3.0)

project(GLAD VERSION 1.0.0.0)

add_library(GLAD STATIC "glad.c" "glad/glad.h" "KHR/khrplatform.h")
target_include_directories(GLAD PUBLIC ${PROJECT_SOURCE_DIR})