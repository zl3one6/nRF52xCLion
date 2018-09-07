cmake_minimum_required(VERSION 3.6)

set(CMAKE_C_STANDARD 99)
set(CMAKE_CXX_STANDARD 98)

set(ARM_TOOLCHAIN_PATH /usr/local/gcc-arm-none-eabi-6-2017-q2-update/bin)
set(ARM_TOOLCHAIN_PREFIX arm-none-eabi-)

add_subdirectory("examples/ble_peripheral/ble_app_hrs/pca10056/s140/armgcc")