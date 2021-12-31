project(enforce)

set(CXX_SOURCES 
    Enforce.cpp)

add_executable(${PROJECT_NAME} ${CXX_SOURCES})

target_include_directories(${PROJECT_NAME} PRIVATE ../src)

target_compile_options (${PROJECT_NAME} PRIVATE -Wall -Wextra)

# target_link_libraries (${PROJECT_NAME} PRIVATE )
