roscore

rosrun dynamixel_sdk_examples read_write_node.py

rosservice call /get_position "id: [ID]"
rostopic pub -1 /set_position dynamixel_sdk_examples/SetPosition "{id: [ID], position: [POSITION]}"