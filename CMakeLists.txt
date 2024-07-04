file(GLOB_RECURSE SOURCES include/*.h)
add_library(glad INTERFACE ${SOURCES})
target_include_directories(glad INTERFACE include)
