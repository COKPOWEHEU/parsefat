Parsefat
--------

The `parsefat` program parses the FAT32 image file and prints the file and directory tree. 
The sample output of the program can be found [here](output.txt).  


### Tested on

* Ubuntu 16.04.4 LTS
* GCC 5.4.0
* GLIBC 2.23
* CMake 3.5.1

### How to build and run the program

1. Install CMake

        sudo apt install cmake
    
1. Build the project

        mkdir build
        cd build
        cmake ..
        make
    
1. Run the example

        ./parsefat disk.img
        
