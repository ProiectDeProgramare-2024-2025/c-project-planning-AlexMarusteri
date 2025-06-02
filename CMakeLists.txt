cmake_minimum_required(VERSION 3.10)
project(ListingProject)

set(CMAKE_CXX_STANDARD 17)
set(SOURCES Listing.cpp ListingManager.cpp)

# Executabilul tău (Alex)
add_executable(user1 Alex.cpp ${SOURCES})

# Executabilul colegului tău (Orlando)
add_executable(user2 Orlando.cpp ${SOURCES})
