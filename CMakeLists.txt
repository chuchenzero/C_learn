cmake_minimum_required(VERSION 3.19)
project(C_learn C)

set(CMAKE_C_STANDARD 11)

add_executable(C_learn
        chapter2/eg1.c
        chapter2/eg2-4-1.c
        chapter2/eg2_1_1_1.c
        chapter2/eg4_plus.c
        chapter2/eg8.c
        chapter3/eg1.c
        chapter3/eg2.c
        chapter4/eg1.c
        chapter4/eg2.c
        chapter4/eg3.c
        chapter4/eg3_1.c
        chapter4/eg4.c
        chapter5/eg1.c
        chapter5/eg2.c
        chapter5/eg3.c
        chapter5/eg4.c
        chapter5/eg4_1.c
        chapter5/tempCodeRunnerFile.c
        chapter6/eg1.c
        chapter6/eg1_2.c
        chapter6/eg2.c
        chapter6/eg3.c
        chapter6/eg3_1.c
        chapter7/eg1.c
        chapter7/eg2.c
        chapter7/eg2_1.c
        eg1_2.c
        eg1_3.c
        hello.c)
add_executable(a hello.c)
add_executable(7_1 chapter7/eg1.c)
add_executable(7_2_1 chapter7/eg2_1.c)