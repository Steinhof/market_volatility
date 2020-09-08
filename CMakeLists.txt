cmake_minimum_required(VERSION 3.17)
project(market_volatility)

set(CMAKE_CXX_STANDARD 20)

add_executable(market_volatility main.cpp qsortd.cpp)