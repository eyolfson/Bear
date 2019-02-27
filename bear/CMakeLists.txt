configure_file(${CMAKE_CURRENT_SOURCE_DIR}/main.py.in ${CMAKE_CURRENT_BINARY_DIR}/grizzly-bear)

include(GNUInstallDirs)
install(PROGRAMS ${CMAKE_CURRENT_BINARY_DIR}/grizzly-bear
    DESTINATION ${CMAKE_INSTALL_BINDIR})
