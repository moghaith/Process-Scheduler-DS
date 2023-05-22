cmake_minimum_required(VERSION 3.24)
project(Process_Scheduler_DS)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Process_Scheduler_DS
        Process.cpp
        Process.h
        Process_Scheduler_DS.cpp
        Process_Scheduler_DS.vcxproj
        Process_Scheduler_DS.vcxproj.filters
        Process_Scheduler_DS.vcxproj.user
        Processor.cpp
        Processor.h
        Scheduler.cpp
        Scheduler.h
        UI.cpp
        UI.h)
