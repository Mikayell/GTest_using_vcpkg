cmake_minimum_required(VERSION 3.6)


project(tests)

find_package(GTest CONFIG REQUIRED)

add_executable(${PROJECT_NAME} myLibTest.cpp)

target_link_libraries(${PROJECT_NAME} PRIVATE GTest::gmock GTest::gtest GTest::gmock_main GTest::gtest_main)
