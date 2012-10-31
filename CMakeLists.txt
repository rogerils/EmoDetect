cmake_minimum_required(VERSION 2.6)
project(CS5780_Term_Project)

# Set version
set(CS5780_Term_Project_VERSION_MAJOR 1)
set(CS5780_Term_Project_VERSION_MINOR 0)

find_package(OpenCV REQUIRED)

include_directories(
    ${OpenCV_INCLUDE_DIR}
    )

link_directories(
    ${OpenCV_LIBRARY_DIRS}
    )

subdirs(src)