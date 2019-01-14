cmake_minimum_required(VERSION 3.12)
project(project)

set(CMAKE_CXX_STANDARD 14)

HEAD
add_executable(project main.cpp A.cpp A.h)
=======
add_executable(project main.cpp B.h B.cpp)
>>>>>>> 71e3a7f7039eaaa72805bb86750270ebb11845b9
