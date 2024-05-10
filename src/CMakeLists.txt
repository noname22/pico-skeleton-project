add_executable(${target_name}
        main.c
        )

# pull in common dependencies
target_link_libraries(${target_name} pico_stdlib)

# create map/bin/hex file etc.
pico_add_extra_outputs(${target_name})
