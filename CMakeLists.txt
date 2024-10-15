idf_component_register(SRCS "src/basicMPU6050.tpp"
                    INCLUDE_DIRS "src/." 
                      REQUIRES arduino-esp32
                      )
project(basicMPU6050)
