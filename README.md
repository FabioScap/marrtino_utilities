Apriltag models in gazebo:

git clone https://github.com/koide3/gazebo_apriltag

cp -R gazebo_apriltag/models/* ~/.gazebo/models/

rm -rf gazebo_apriltag


TODO: aggiungere i blocchi condizionali nei file xacro per non caricare i link relativi alla simulazione (specialmente gazebo_camera)
