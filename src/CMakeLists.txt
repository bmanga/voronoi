ADD_EXECUTABLE( voronoi test_voronoi.cpp)
message(STATUS "conan libs are " ${CONAN_LIBS})
TARGET_LINK_LIBRARIES( voronoi ${CONAN_LIBS} dc1394)


