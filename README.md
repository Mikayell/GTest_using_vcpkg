# GTest_using_vcpkg

In order to build this project, use this code:

cmake -B [build directory] -S . -DCMAKE_TOOLCHAIN_FILE=[path to vcpkg]/scripts/buildsystems/vcpkg.cmake

Then build with:

cmake --build [build directory]
