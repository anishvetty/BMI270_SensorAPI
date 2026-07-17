idf_component_register(
    SRCS
        "bmi2.c"
        "bmi270.c"
        "bmi2_ois.c"
        "bmi270_context.c"
        "bmi270_legacy.c"
        "bmi270_maximum_fifo.c"
    INCLUDE_DIRS
        "."
    REQUIRES
        driver           # for I2C/SPI if you use ESP-IDF's driver APIs
)
