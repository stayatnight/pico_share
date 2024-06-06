add_executable(hello hello.c)

target_link_libraries(hello pico_stdlib)
pico_add_extra_outputs(hello)
