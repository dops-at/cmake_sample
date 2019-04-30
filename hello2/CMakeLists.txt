add_executable(hello2 cpp/hello2.cpp)
install(TARGETS hello2 OPTIONAL RUNTIME DESTINATION bin LIBRARY DESTINATION bin)
