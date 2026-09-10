cmake_minimum_required(VERSION 4.3)
project(ray_tracing)

set(CMAKE_CXX_STANDARD 20)

add_executable(ray_tracing main.cpp
        vec3.h
        color.h
        ray.h
        hittable.h
        sphere.h
        hittable_list.h
        rtweekend.h
        interval.h
        camera.h
        material.h
        aabb.h
        bvh.h
        texture.h
        rtw_stb_image.h
        perlin.h
        quad.h)
