cmake_minimum_required(VERSION 3.0.0)
# TODO: change template to project name
project(template VERSION 0.1.0)

add_subdirectory(app)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
