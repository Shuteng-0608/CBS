# CBS
The code mainly come from [here](https://github.com/enginbaglayici/ConflictBasedSearch).

## Install Library
Building the library needed first from [this repository](https://github.com/Shuteng-0608/CBS/tree/main)

## Compile and run
    cd catkin_ws/src/
    git clone https://github.com/Shuteng-0608/CBS/tree/main-catkin
    cd ..
    catkin_make -DCATKIN_WHITELIST_PACKAGES="CBS"
    source ./devel/setup.bash
    rosrun CBS main
