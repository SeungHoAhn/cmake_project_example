cmake_minimum_required(VERSION 3.14)

set(PROJECT_NAME cmake_project_example) #변수설정하는 부분
set(CMAKE_CXX_STANDARD 17) # c++ 17버전

project(${PROJECT_NAME})
add_executable(${PROJECT_NAME} src/main.cpp) #실행파일을 만듬.
