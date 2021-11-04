
add_executable(distance_transform distance_transform.cpp distance_transform.h example.cpp)
target_link_libraries(distance_transform ${OpenCV_LIBS})