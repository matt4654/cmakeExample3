cmake_minimum_required(VERSION 3.12)

project(MyProject VERSION 1.0)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(sayHello)
add_subdirectory(helloExe)


target_compile_features(${PROJECT_NAME} PUBLIC cxx_std_20)

