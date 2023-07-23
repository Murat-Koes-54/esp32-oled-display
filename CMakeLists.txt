cmake_minimum_required(VERSION 3.5)

set(EXTRA_COMPONENT_DIRS "${EXTRA_COMPONENT_DIRS} ./src/main/")

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(ebx_esp32s3pro_oled_display)
