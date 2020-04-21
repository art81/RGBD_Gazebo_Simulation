# RGBD_Gazebo_Simulation
Simple gazebo simulation with a python script that subscribes to a gazebo simulated RGBD camera.

Processing being done was for EECS 531 (Computer Vision) at Case Western Reserve University with Chude (Frank) Qian Spring 2020.

### Running the Code

roslaunch gazebo_ros empty_world.launch

Navigate to the "insert" tab on gazebo and add the Gazebo_Models folder to the path -> You can now drag and drop the Kinect object into the environment and it will immediately start publishing data to the following topics (can change them in model.sdf file in Kinect model folder):

/camera/color/camera_info

/camera/color/image_raw

/camera/color/image_raw/compressed

/camera/color/image_raw/compressed/parameter_descriptions

/camera/color/image_raw/compressed/parameter_updates

/camera/color/image_raw/compressedDepth

/camera/color/image_raw/compressedDepth/parameter_descriptions

/camera/color/image_raw/compressedDepth/parameter_updates

/camera/color/image_raw/theora

/camera/color/image_raw/theora/parameter_descriptions

/camera/color/image_raw/theora/parameter_updates

/camera/depth/camera_info

/camera/depth/image_raw

/camera/depth/points

/camera_ir/parameter_descriptions

/camera_ir/parameter_updates
