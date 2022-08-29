# SPREADS - Contirbuted by WHU-CVRS and Didi Inc. 

The repository is estabilished for the project with Didi, which establishs an ultimate toolbox for the optical camera calibration problem. We named the System "SPREADS", which represented *"SPace REconstruction And Detection System"*. The toolbox is named "Meta-Board" and "Meta-CalibToobox".

# Usage
## Dependency
### Log
Glog

### Algorithm

### Build
```shell
# step-1 : create the build directory
mkdir build && cd build

# step-2 : use cmake to configurate the code.
## for debug version
cmake .. -DCMAKE_BUILD_TYPE=Debug

## for release version
cmake ..

# step-3 : run the code.
# run the code.
./spreads
```
