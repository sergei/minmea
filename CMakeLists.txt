set(sources
        ./minmea.c
        )

idf_component_register(SRCS ${sources}
        INCLUDE_DIRS ./
        )
