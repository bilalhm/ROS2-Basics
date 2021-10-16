# ROS2-Basics
Writing a Simple Publisher and Subscriber (Python)
I)create package:
    • create new file ros2_ws thene new file  src
    • cd ros2_ws/src/
    • ros2 pkg create --build-type ament_python py_topic
II)Create python code
    • after create package we see a new file so we go in file named py_topic and we create two page python with name py_sub_spiral .py and py_pub_spiral.py
    • and we put code there
III)Change 
we change two pages by two pages setup.py and package.xml

IV) Colcon build
in the first page of terminal we wreat
    • ~$ cd     ros2_ws/src/
    • ~/ros2_ws/src$    cd ..
    • ~/ros2_ws$   colcon build
V)Run turtle
in the fiveth terminal we wreate
    • ~/ros2_ws$ ros2 run turtlesim turtlesim_node
VI)Run pub and sub
in the second terminal we wreat 
    • ~/ros2_ws$ source install/setup.bash
    • ~/ros2_ws$ ros2 run py_topic py_pub_spiral 2.0 2.0 0.2
in the tiered terminal we wreate
    • ~/ros2_ws$ source install/setup.bash
    • ~/ros2_ws$ ros2 run py_topic py_sub_spiral
