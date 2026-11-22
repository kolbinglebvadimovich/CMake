cmake_minimum_required(VERSION 3.20)
project(my_geometry_project)
set(CMAKE_CXX_STANDARD 17)
add_executable(my_geometry_program
main.cpp
Figure.h Figure.cpp
Triangle.h Triangle.cpp
RightTriangle.h RightTriangle.cpp
IsoscelesTriangle.h IsoscelesTriangle.cpp
EquilateralTriangle.h EquilateralTriangle.cpp
Quadrangle.h Quadrangle.cpp
Rectangle.h Rectangle.cpp
Square.h Square.cpp
Parallelogram.h Parallelogram.cpp
Rhombus.h Rhombus.cpp
)