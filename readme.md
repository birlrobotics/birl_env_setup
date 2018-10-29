# Why do we have this repo?
In order to setup kitting experiment quickly, using this repo can download all the related packages
1. Download rosinstall[rosinstall wiki](http://wiki.ros.org/rosinstall)
`sudo apt-get install python-rosinstall`
2. run this command
`rosinstall path_to_place_youwanna_put birl_kitting_sdk.rosinstall`

# simple example
`- git:
    local-name: birl_tactile_sensor
    uri: https://github.com/birlrobotics/birl_tactile_sensor.git
    version: master`
* local-name: the name will be saved in your workspace
* uri: git link
* version: which branch you wanna download
