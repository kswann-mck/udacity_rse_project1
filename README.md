# udacity_rse_project1
Udacity Robotics Software Engineer Project 1: Build My World

This is a simple word which includes a single story floor plan with a number of rooms with standard gazebo desk
models in them, as well as two instances of a four wheeled robot.

Installation:

- Install gazebo: [http://gazebosim.org/tutorials?tut=install_ubuntu](http://gazebosim.org/tutorials?tut=install_ubuntu)
- Clone this repository: `git clone https://github.com/kswann-mck/udacity_rse_project1.git`
- `cd udacity_rse_project1`
- `mkdir build && cd build`
- `cmake ../`
- `make`
- `cd ../world/`
- `export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:<path to folder>/udacity_rse_project1/build`

Run:

- From the root directory: `cd world`
- `gazebo world1`

Optional to run on osx export the following env variables before running the above command:
```
export CMAKE_PREFIX_PATH=${CMAKE_PREFIX_PATH}:/usr/local/opt/tbb@2020_u3
export CPATH=${CPATH}:/usr/local/opt/tbb@2020_u3/include
export LIBRARY_PATH=${LIBRARY_PATH}:/usr/local/opt/tbb@2020_u3/lib
```

You should see the message `Welcome to Kitson's World` print to the console when the above command is run.
