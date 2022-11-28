cmake_minimum_required(VERSION 3.1)
project(osx-elf-header)

add_library(osx-elf-header INTERFACE)
target_include_directories(osx-elf-header INTERFACE include/)
