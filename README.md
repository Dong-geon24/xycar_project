# xycar_project
xycar project simulation and sim2real

ros version: ros1 melodic

    #terminal1
    $ roslaunch rosbridge_server rosbridge_websocket.launch


    #terminal 2
    $ source /opt/ros/melodic/setup.bash
    $ source xycar_ws/devel/setup.bash
    $ roslaunch driving driving.launch

    #terminal2
    sourcing
    $ cd xycar_ws/src/xycar_sim_driving
    $ ./xycar3Dsimulator.x86_64
    
