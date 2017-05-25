cmake_minimum_required(VERSION 2.8)

set(main_SRCs main.cpp)

ADD_EXECUTABLE(main ${main_SRCs})
ADD_LIBRARY(hell ${main_SRCs})