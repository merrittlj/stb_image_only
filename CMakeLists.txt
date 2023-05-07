set(LIBRARY_INCLUDE_DIR "${CMAKE_CURRENT_SOURCE_DIR}/include/")

add_library(stb INTERFACE)  # this is an header-only library.

target_include_directories(stb INTERFACE ${LIBRARY_INCLUDE_DIR})
