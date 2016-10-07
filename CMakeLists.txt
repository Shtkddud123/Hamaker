cmake_minimum_required (VERSION 1.0)
project (Hamaker_Potential)

include_directories("${PROJECT_SOURCE_DIR}/src")
include_directories("${PROJECT_SOURCE_DIR}/include")

add_subdirectory (src)
#add_subdirectory (include)
add_executable (main main.cpp)
target_link_libraries (main src)

