find_package(PhysFS REQUIRED)
add_library(physfs++ physfs.cpp)
target_include_directories(physfs++ PUBLIC ${PHYSFS_INCLUDE_DIR})
target_link_libraries(physfs++ ${PHYSFS_LIBRARY})
