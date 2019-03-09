cmake_minimum_required(VERSION 3.5)
project(GPS_INS_Fusion)

set(CMAKE_PREFIX_PATH 
    ${PROJECT_SOURCE_DIR} "/lib/Eigen")
set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES 
    ${PROJECT_SOURCE_DIR}/src/ekf.cpp
    ${PROJECT_SOURCE_DIR}/src/ekf.hpp
    ${PROJECT_SOURCE_DIR}/src/fusion.cpp
    ${PROJECT_SOURCE_DIR}/src/fusion.hpp
    ${PROJECT_SOURCE_DIR}/src/geo_ned.cpp
    ${PROJECT_SOURCE_DIR}/src/geo_ned.hpp
    ${PROJECT_SOURCE_DIR}/src/main.cpp
    ${PROJECT_SOURCE_DIR}/src/parameterReader.hpp
    ${PROJECT_SOURCE_DIR}/src/fusion.cpp
    ${PROJECT_SOURCE_DIR}/src/run_fusion.cpp
    ${PROJECT_SOURCE_DIR}/src/utils.cpp
    ${PROJECT_SOURCE_DIR}/src/utils.hpp
)

add_executable(GPS_INS_Fusion ${SOURCE_FILES})
