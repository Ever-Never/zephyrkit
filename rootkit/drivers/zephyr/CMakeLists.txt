# Device driver subdirectories

zephyr_include_directories(.)

add_subdirectory_ifdef(CONFIG_MISC              misc)
add_subdirectory_ifdef(CONFIG_ADC               adc)
add_subdirectory_ifdef(CONFIG_DISPLAY           display)
add_subdirectory_ifdef(CONFIG_SERIAL_HAS_DRIVER serial)
add_subdirectory_ifdef(CONFIG_GPIO              gpio)
add_subdirectory_ifdef(CONFIG_I2C               i2c)
add_subdirectory_ifdef(CONFIG_SPI               spi)
add_subdirectory_ifdef(CONFIG_FLASH             flash)
add_subdirectory_ifdef(CONFIG_BT                bluetooth)
add_subdirectory_ifdef(CONFIG_TIMER             timer)
add_subdirectory_ifdef(CONFIG_PWM               pwm)
add_subdirectory_ifdef(CONFIG_MOTOR_PWM         led)
add_subdirectory_ifdef(CONFIG_SENSOR            sensor)
add_subdirectory_ifdef(CONFIG_KSCAN             kscan)
add_subdirectory_ifdef(CONFIG_NETWORKING        net)
add_subdirectory_ifdef(CONFIG_GPS               gps)
add_subdirectory_ifdef(CONFIG_MPSL              mpsl)
add_subdirectory_ifdef(CONFIG_MCUBOOT           hw_cc310)

