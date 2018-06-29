cmake_minimum_required(VERSION 3.2) #minimum required version of CMake
project(NSIS_Sample) #set solution name

#Set version number
Set(NSIS_Sample_VERSION_MAJOR 1)
Set(NSIS_Sample_VERSION_MINOR 0)

#Add an executable
file(GLOB src *.h *.cpp) # generate a list of all files that match the globbing expressions into src variable

add_executable(ExeName ${src}) #add a .exe project