add_library(dywapitchtrack STATIC
    src/dywapitchtrack.c
)
target_include_directories(dywapitchtrack
    PUBLIC
        src
)