cmake_minimum_required(VERSION 3.7)
project(JPS_B)


include_directories(Source)
add_executable(${PROJECT_NAME}
        source/Base.h
        source/BitArray.h
        source/CoreTypeDef.h
        source/JPSCollision.cpp
        source/JPSCollision.h
        source/JPSHeap.h
        source/JPSPath.cpp
        source/JPSPath.h
        source/main.cpp
        )
