cmake_minimum_required (VERSION 3.10)
project (Test)
enable_testing()
add_executable(Test test_main.c ../project_src.c)
include_directories(..)
add_test(NAME Test COMMAND Test)