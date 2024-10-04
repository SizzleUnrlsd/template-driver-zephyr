zephyr_library()
zephyr_library_sources(bma400.c)

# This shouldn't be needed if we send this driver upstream.
zephyr_include_directories(.)
