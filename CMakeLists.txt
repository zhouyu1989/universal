cmake_minimum_required(VERSION 3.0)
project(universal CXX)
include(ExternalProject)

install(DIRECTORY ./res/media       DESTINATION ${CMAKE_INSTALL_DIR}/opt)
install(DIRECTORY ./res/light       DESTINATION ${CMAKE_INSTALL_DIR}/opt)
install(DIRECTORY ./workdir_asr_cn       DESTINATION ${CMAKE_INSTALL_DIR}/system)
