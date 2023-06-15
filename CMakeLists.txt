cmake_minimum_required(VERSION 3.8)
project(UsingSol2WithCMake)

set(CMAKE_CXX_STANDARD 20)

# Find lua
find_package(Lua REQUIRED)

# Find sol2
find_package(sol2 CONFIG REQUIRED)

# Create the executable target
add_executable(UsingSol2WithCMake "UsingSol2WithCMake.cpp")

# Link against lua
target_link_libraries(UsingSol2WithCMake ${LUA_LIBRARIES})