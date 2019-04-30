# try to build and install only hello2
* rm -rf build
* cmake -S . -B build -DCMAKE_SKIP_INSTALL_ALL_DEPENDENCY=ON
* cmake --build build --target hello2
* cmake --build build --target install

# try to build and install only hello
* rm -rf build
* cmake -S . -B build -DCMAKE_SKIP_INSTALL_ALL_DEPENDENCY=ON
* cmake --build build --target hello
* cmake --build build --target install
