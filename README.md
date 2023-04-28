# Udacity-Motion-Planning-and-Decision-Making-Project
This is my project for Udacity Self Driving Cars Nano Degree Fourth Module Motion Planning and Decision Making Project
find video for project running in following link
https://youtu.be/-TW3NbvmcvI



# How to launch?
New terminal window
1. su - student
// Will say permission denied, ignore and continue 
2. cd /opt/carla-simulator/
3. SDL_VIDEODRIVER=offscreen ./CarlaUE4.sh -opengl

New terminal window
4. git clone https://github.com/udacity/nd013-c5-planning-starter.git
5. Stop here now it's needed to replace the codes open nd013-c5-planning-starter/project/starter_files
6. delete the five file having same name as above
7. upload those five files now
8. cd nd013-c5-planning-starter/project
9. ./install-ubuntu.sh
10. cd starter_files/
11. cmake .
12. make
13. cd nd013-c5-planning-starter/project
14. ./run_main.sh

// This will silently fail 
15. ctrl + C to stop 
16. ./run_main.sh again
17. Go to desktop mode to see CARLA

Thank you
