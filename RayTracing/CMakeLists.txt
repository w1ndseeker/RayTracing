project(raytracing_app)

set(CMAKE_CXX_STANDARD 17)

aux_source_directory(${CMAKE_CURRENT_SOURCE_DIR}/src DIR_APP_SRC)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../Walnut/Walnut/src)
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../Walnut/vendor/imgui)

add_executable(ray_tracing_demo ${DIR_APP_SRC})
target_link_libraries(ray_tracing_demo walnut)