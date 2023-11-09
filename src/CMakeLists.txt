add_executable(pico_project_skeleton
        main.c
        )

# pull in common dependencies
target_link_libraries(pico_project_skeleton pico_stdlib)

# create map/bin/hex file etc.
pico_add_extra_outputs(pico_project_skeleton)
