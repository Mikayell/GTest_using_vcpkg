# GTest_using_vcpkg

In order to build this project, use this code:

cmake -B [build directory] -S . -DCMAKE_PREFIX_PATH=[path to gtest installed by vcpkg]

Then build with:

cmake --build [build directory]
