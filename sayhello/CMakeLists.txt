add_library(sayhello SHARED headers/sayhello.h cpp/sayhello.cpp)
target_include_directories(sayhello PUBLIC cpp headers)
install(TARGETS sayhello OPTIONAL RUNTIME DESTINATION bin LIBRARY DESTINATION bin)
