project(Test)

include_directories("${CMAKE_CURRENT_SOURCE_DIR}/../gtest")

add_executable(Test tests.cpp test_main.cpp)

target_link_libraries(Test gtest Plex Line Point Square Circle Canvas)