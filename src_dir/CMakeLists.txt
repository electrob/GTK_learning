link_directories(
    ${GTKMM_LIBRARY_DIRS}  )

include_directories(
    ${GTKMM_INCLUDE_DIRS}  )

add_executable(helloworld # name of the executable on Windows will be example.exe 
    main.cc 
    helloworld.cc 
    helloworld.h )

target_link_libraries(helloworld 
    ${GTKMM_LIBRARIES}  )
