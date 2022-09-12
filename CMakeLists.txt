cmake_minimum_required(VERSION 3.18)

set(LLVM_MOS_PLATFORM c64)
find_package(llvm-mos-sdk REQUIRED)
project(llvm-mos-sdk-foo)


add_executable(helo
	src/main.cc
)

set_property(TARGET helo PROPERTY CXX_STANDARD 20)

