cmake_minimum_required (VERSION 3.10)

file(GLOB sourceFiles 
    "./libgif/include/*.h"
    "./libgif/source/*.c"
)

add_library (libgif ${sourceFiles} )
include_directories(./libgif/include)