INCLUDE_DIRECTORIES(${PROJECT_SOURCE_DIR}/src ${GNULIBS_INCLUDE_DIR})
LINK_LIBRARIES(${PROJECT_NAME} ${REQUIRED_LIBRARIES} )

ADD_EXECUTABLE(aruco_test_svm  aruco_test_svm.cpp)

INSTALL(TARGETS aruco_test_svm RUNTIME DESTINATION bin)

