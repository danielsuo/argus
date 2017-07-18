cmake_minimum_required (VERSION 3.5)
project (argus)

find_package (OpenCV REQUIRED)
include_directories (${OpenCV_INCLUDE_DIRS})

file (GLOB_RECURSE SOURCE_FILES ${CMAKE_CURRENT_SOURCE_DIR}/src/*.cpp)

add_executable (${PROJECT_NAME} ${SOURCE_FILES})
target_link_libraries (DisplayImage ${OpenCV_LIBS})
