zephyr_library()

zephyr_library_sources_ifdef(CONFIG_BMM150 bmm150.c)
