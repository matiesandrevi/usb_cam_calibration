# usb_cam_calibration
Calibration of an usb camera using usb_cam and camera_calibration ROS packages
To calibrate a camera

$ roslaunch usb_cam_calibration usb_camera_calibration.launch video_device:="/dev/video1"

To see raw and rectified images after calibration

$ roslaunch usb_cam_calibration usb_camera_calibrated.launch video_device:="/dev/video1"
