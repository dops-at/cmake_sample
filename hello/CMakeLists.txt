add_executable(hello cpp/hello.cpp)
target_link_libraries(hello sayhello)
install(TARGETS hello OPTIONAL RUNTIME DESTINATION bin LIBRARY DESTINATION bin)
