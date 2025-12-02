cmake_minimum_required(VERSION 3.10)

# 프로젝트 이름
project(RayTracingInOneWeekend)

# C++ 표준 설정
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 실행 파일 생성 (튜토리얼 이름으로)
add_executable(rio main.cpp)
