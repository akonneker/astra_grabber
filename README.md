# astra_grabber
A simple utility for capturing and logging images from an Orbbec Astra RGBD camera

# Building & running

Modify lines 15 & 16 of ./src/CMakeLists.txt to point to the headers and lib files of your orbbbec astra driver installation.

Navigate to ./build and type 'cmake ..' followed by 'make'

This will put a binary called 'snapshot' into the ./build/bin directory.

Before running the program, change the config.toml file to your specifications.

When running the program, pass the config file path as an argument.
