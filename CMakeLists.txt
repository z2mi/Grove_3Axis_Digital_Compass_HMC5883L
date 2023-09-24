cmake_minimum_required(VERSION 3.5)
set ( HMC5883L_SRCS
      "HMC5883L.cpp"
) 
idf_component_register(SRCS ${HMC5883L_SRCS}
                    INCLUDE_DIRS "."
                    REQUIRES "arduino" # Library requires Arduino
                    )

project(HMC5883L)