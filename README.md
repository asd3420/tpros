# tpros
Installation



Partie 1

`cd marker_ws
source devel/setup.bash
roscore
rosrun marker_visualiser publish_marker.py /visualization_marker:=/marker_test
rviz`

Partie 2

source devel/setup.bash
roscore
rosrun marker_visualiser publish_marker_array.py /visualization_marker:=/space_delimiter
rviz

Partie 3

source devel/setup.bash
roscore
rosrun marker_visualiser randomwalk.py
rviz

Partie 4

source devel/setup.bash
roscore
rosrun marker_visualiser random_walk.py
rviz
