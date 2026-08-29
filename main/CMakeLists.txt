idf_component_register(
    SRCS "station_example_main.c" "osc.c"
    INCLUDE_DIRS "."
    REQUIRES esp-osc esp_wifi nvs_flash
)
