cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "C:/Projects/s3-personal-LarsLT/Code/esp/cleanRTOS/components/CleanRTOS/src/CleanRTOS.h" # mian cpp file of library
                    INCLUDE_DIRS "src/." #include src folder, change to "." if no src
                    REQUIRES "arduino-esp32"
                    )
    
project(CleanRTOS) # (Name of the folder)