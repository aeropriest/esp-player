# The following lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.5)

# include($ENV{ADF_PATH}/CMakeLists.txt)
include(/Users/ashokjaiswal/esp/esp-adf/CMakeLists.txt)

# include($ENV{IDF_PATH}/tools/cmake/project.cmake)
# include(/Users/ashokjaiswal/esp/esp-idf/tools/cmake/project.cmake)
include(/Users/ashokjaiswal/esp/esp-adf/esp-idf/tools/cmake/project.cmake)
project(check_board_buttons)
