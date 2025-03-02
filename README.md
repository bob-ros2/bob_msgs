# ROS Package bob_msgs
Message and Service definitions for Bob's ROS Nodes.

## Messages
### TTImage

**Message specification:**  [TTImage.msg](https://github.com/bob-ros2/bob_msgs/blob/main/msg/TTImage.msg)
> sensor_msgs/Image image\
  string caption\
  string json

## Services
### SetSequence
Used by bob_face.bag node to set face animation.

**Message specification:** [SetSequence.srv](https://github.com/bob-ros2/bob_msgs/blob/main/srv/SetSequence.srv)

> uint8 TYPE_CIRCULAR=0\
  uint8 TYPE_FLIPFLOP=1\
  uint8 type\
  uint8 rate\
  uint32 start\
  uint32 end\
  ---\
  string error
