# ROS on Mac M1 
#### This is a simple guide on how to install ROS on MacOS, especially the M1 chips. There used to be 2 ways to do it on Mac M1 using UTM, One was the ISO image install, and the other was the Server install. Now only the server install works.
</br>
</br>

## Install the Server Image of Ubuntu 20.04
This is the better way.
1. Go to : https://cdimage.ubuntu.com/releases/20.04/release/
2. Install the ARM image
</br>
</br>

## Install UTM Virtual Machine:
We will be running Ubuntu on a virtual machine:
1. Go to : https://mac.getutm.app/
2. Install UTM 
4. Set up Ubuntu server on UTM. This video can be used for reference : https://www.youtube.com/watch?v=6mtfncj9vhU . If any install error is faced, try putting --fix-missing in the end of the command and do again. Instead of installing ubuntu-desktop, install kde, it is faster and better. The only downside being that gazebo opens in small size.
5. While installation, it will show the option of "Try Ubuntu" and "Install Ubuntu", you have to choose the former, then follow the instructions of the video provided above.
</br>
</br>

## Set-up ROS
We will now set up ROS on the system
1. This reference can be taken to install ROS on the system : http://wiki.ros.org/noetic/Installation/Ubuntu
</br>
</br>

## Set-up Turtlebot
We will now install Turtle Bot
1. This reference can be taken to install Turtlebot : https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/
2. If 1. doesn't work : https://automaticaddison.com/how-to-launch-the-turtlebot3-simulation-with-ros/
</br>
</br>

## VS Code installation
1. The following video can be taken as reference : https://youtu.be/Y1fei1mzP7Q
2. If VS Code shows a blank screen on opening, then the problem can be corrected using the procedure given by johnhidney on : https://github.com/Microsoft/vscode/issues/6379. This issue is faced mainly in server install (B.) and even after solving it, it works only when VS Code is opened via terminal

