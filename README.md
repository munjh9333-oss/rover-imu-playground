# rover-imu-playground
repo/
 ├─ firmware/  ├─ ros2_ws/  ├─ scripts/  ├─ docs/  ├─ results/  ├─ README.md

mkdir -p ~/rover_ws/src && cd ~/rover_ws
ros2 pkg create --build-type ament_cmake rover_bringup
git init && git remote add origin <repo-url>
