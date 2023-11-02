# agv_model
URDF Launch file for agv_model

#Clone into src folder inside ros2 works space
"git clone https://github.com/Mathewtomy1620/agv_model.git"
#From ros2 works space, build the package
"colcon build --packages-select agv_model_description"
#Then source the setup.bash file
#Launch command:
"ros2 launch agv_model_description display.launch.py"
