# collab-robotics-homework
Homework code for collaborative robotics. Be sure to push all written code and commit to this git repository, as the code will live under mounted/

Using peasant98/tidybot2:humble:

Mounting docker container startup:

docker run -d \
  --name collab-tidybot-novnc \
  -p 6080:80 \
  --shm-size=2g \
  -v /mnt/c/Users/jacka/Documents/Schoolwork/collab-robotics-homework/mounted:/home/ubuntu/Documents \
  peasant98/tidybot2:humble

Location of where source code for scripts need to go, right now I just copy and paste from mounted, treating the image as a temporary working directory.
/opt/tidybot2/ros2_ws/install/tidybot_bringup/lib/tidybot_bringup/trajectory_tracking.py
