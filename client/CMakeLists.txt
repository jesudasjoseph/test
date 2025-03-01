# client

set(SOURCE_DIR "src")

set(SOURCES
  src/main.cpp
)

add_executable(client ${SOURCES})
target_link_libraries(client glfw)
target_link_libraries(client glad)
target_link_libraries(client glm)