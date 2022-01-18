# CMakeLists.txt --- CMake project settings
#    ex) cmake -G "Visual Studio 9 2008" .
#    ex) cmake -DCMAKE_BUILD_TYPE=Release -G "MSYS Makefiles" .
##############################################################################

# CMake minimum version
cmake_minimum_required(VERSION 3.0)

# project name and language
project(Won32 C)

# sub-directories
add_subdirectory(WonAlphaBlend)
add_subdirectory(WonFileID)
add_subdirectory(WonGetDiskFreeSpaceEx)
add_subdirectory(WonGradientFill)
#add_subdirectory(WonSetThreadUILanguage) # header-only
add_subdirectory(WonTransparentBlt)

##############################################################################
