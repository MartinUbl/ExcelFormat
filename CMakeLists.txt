IF(BIICODE)
   INCLUDE("cmake/biicode.cmake")
   RETURN()
ENDIF()

cmake_minimum_required(VERSION 3.1)

SET(CMAKE_CXX_STANDARD 17)

project(ExcelFormat)

include("cmake/Build.cmake")
include("cmake/Install.cmake")
