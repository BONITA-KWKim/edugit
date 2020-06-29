cmake_minimum_required (VERSION 3.5.1)

add_definitions (-std=c++11)

## hello
set (HELLO_FILES ${CMAKE_CURRENT_SOURCE_DIR}/hello.cc)
add_executable (hello ${HELLO_FILES})

## targets
add_custom_target (run_hello
  COMMAND hello
  WORKING_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR}
  COMMENT "run generated hello in ${CMAKE_CURRENT_BINARY_DIR}"
  SOURCES ${HELLO_FILES}
)