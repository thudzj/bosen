cmake_minimum_required(VERSION 2.8)

set(CMAKE_MODULE_PATH ${CMAKE_SOURCE_DIR}/cmake/modules)

add_subdirectory(third_party)
add_subdirectory(src)
add_subdirectory(app/dml)
add_subdirectory(app/dnn)
add_subdirectory(app/dnn_speech)
add_subdirectory(app/kmeans)
add_subdirectory(app/mlr)
add_subdirectory(app/NMF)
add_subdirectory(app/rand_forest)
add_subdirectory(app/sparsecoding)
