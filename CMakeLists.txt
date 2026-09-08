cmake_minimum_required(VERSION 4.3)
project(raytracig)

set(CMAKE_CXX_STANDARD 20)

add_executable(raytracig main.cpp
        vec3.h
        color.h
        ray.h
        hittable.h
        sphere.h
        hittable_list.h
        rtweekend.h
        interval.h
        camera.h)
