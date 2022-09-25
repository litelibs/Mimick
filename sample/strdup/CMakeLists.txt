if (NOT MSVC)
    set_source_files_properties (test.c PROPERTIES COMPILE_FLAGS -O0)
endif ()