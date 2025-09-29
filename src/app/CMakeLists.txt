qt_add_executable(SPMT
    main.cpp)

target_link_libraries(SPMT PRIVATE Qt6::Widgets)

set_target_properties(SPMT PROPERTIES
    )