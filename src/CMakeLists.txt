# Generic test that uses conan libs
add_executable(intro main.cpp)
target_link_libraries(

  PUBLIC project_options project_warnings)

