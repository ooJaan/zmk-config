if(CONFIG_PINMUX)
zephyr_library()
zephyr_library_include_directories(${ZEPHYR_BASE}/drivers)
endif()
