add_executable(vs_std_future vs_std_future.cpp)
target_link_libraries(vs_std_future var_futures Threads::Threads benchmark)