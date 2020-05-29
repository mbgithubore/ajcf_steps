add_executable(account main.cpp)

add_test(NAME musify-welcome  COMMAND musify-welcome)

target_link_libraries(musify PRIVATE common_settings)