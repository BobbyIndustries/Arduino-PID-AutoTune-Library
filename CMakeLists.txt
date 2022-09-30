# Adafruit Bus IO Library
# https://github.com/adafruit/Adafruit_BusIO
# MIT License

cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "PID_AutoTune_v0/PID_AutoTune_v0.cpp" 
                       INCLUDE_DIRS "PID_AutoTune_v0"
                       REQUIRES arduino)

project(PID-AutoTune-v0)
