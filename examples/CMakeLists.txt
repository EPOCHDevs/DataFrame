add_executable(hello_world hello_world.cc)

find_package(TBB CONFIG REQUIRED)

target_link_libraries(hello_world PRIVATE DataFrame TBB::tbb )
