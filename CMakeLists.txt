cmake_minimum_required (VERSION 2.6)
project (eli_os_extra)

file(GLOB eli_proc_extra_utils_sources ./src/**.c)
SET(eli_os_extra ${eli_proc_extra_utils_sources})

ADD_LIBRARY (eli_os_extra ${eli_os_extra})
TARGET_LINK_LIBRARIES (eli_os_extra)