# try to build and install
* rm -rf build
* cmake -S . -B build -DCMAKE_SKIP_INSTALL_ALL_DEPENDENCY=ON
* cmake --build build --target hello2
* cmake --build build --target install
