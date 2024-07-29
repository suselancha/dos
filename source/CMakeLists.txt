cmake_minimum_required (VERSION 3.8)
project(DosApp)
add_executable (DosAppBinary uno.cpp)
target_compile_features(DosAppBinary PRIVATE cxx_std_14)