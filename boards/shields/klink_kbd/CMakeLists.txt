# Copyright (c) 2025 YANG
# zmk klink indicator
zephyr_library()
zephyr_library_include_directories(${CMAKE_SOURCE_DIR}/include)
zephyr_library_sources(klink_indicator.c)