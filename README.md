$ roslaunch rtabmap_launch rtabmap.launch \
    args:="--delete_db_on_start" \
    rgb_topic:=/camera/color/image_raw \
    depth_topic:=/camera/depth/image_raw \
    camera_info_topic:=/camera/color/camera_info \
    imu_topic:=/imu \
    frame_id:=base_link \
    odom_frame_id:=odom \
    approx_sync:=true \
    wait_imu_to_init:=true \
