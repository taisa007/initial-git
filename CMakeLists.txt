cmake_minimum_required(VERSION 3.3)
project(initial_git)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
        #cache.h
        init-db.c
        #update-cache.c
        #write_tree.c
        #read-cache.c
        #commit-tree.c
)

add_executable(initial_git ${SOURCE_FILES})