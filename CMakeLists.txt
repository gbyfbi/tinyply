cmake_minimum_required(VERSION 2.8)
project(Tinyply)

set(CMAKE_CXX_STANDARD 11)

include_directories(source)
#FILE(GLOB_RECURSE sourcefiles "src/*.cpp")
add_executable(example source/example.cpp source/tinyply.cpp )
#target_link_libraries(ex ${OpenCV_LIBS})



