# itu-rover_my-contributions

imu_udp.py -> this script is a ROS node that listens for custom 64-byte binary UDP packets from a microprocessor connected to the IMU, translates them into standard sensor_msgs/Imu messages, and publishes them on the /imu/data topic.
