# About
This package controls the cameras installed on the catvehicle testbed. 

# Install
To install the daemon onto ironwood in the car

```
cd catvehicle_ws
rosrun robot_upstart install catvehiclecameras/launch/cameras.launch --master http://rtd4.local:11311 --interface eth0 --user root
```

## why root?
If you do not run the process as root, then there are access problems with the firewire cable. 
This should be fixed in a future release, and/or might be easy to fix if someone knows how to do it.

# Acknowledgements
Copyright (c) 2017 Arizona Board of Regents

## License
BSD 3-Clause. 

## Author
Jonathan Sprinkle
sprinkjm@email.arizona.edu
