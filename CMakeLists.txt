CMAKE_MINIMUM_REQUIRED(VERSION 3.14)
SET(CMAKE_C_STANDARD 11)

PROJECT(rax C)
MESSAGE(STATUS "Building rax library...")

ADD_LIBRARY(rax STATIC
	rax.c)
