find_package(Poco REQUIRED COMPONENTS Net)

add_executable(poco_example poco_example.cc)
target_link_libraries(poco_example PRIVATE Poco::Net)
