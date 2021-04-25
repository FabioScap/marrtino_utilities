Apriltag models in gazebo:

git clone https://github.com/koide3/gazebo_apriltag

cp -R gazebo_apriltag/models/* ~/.gazebo/models/

rm -rf gazebo_apriltag


TODO: aggiungere i blocchi condizionali nei file xacro per non caricare i link relativi alla simulazione (specialmente gazebo_camera)


dock.py:
Per avvicinarsi a 30cm da tag0
rosrun tf static_transform_publisher 0 0 0.30 0 1.5707 -1.5707 tag0 dock_frame 10 
