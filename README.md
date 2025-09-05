# Synchronous-Drive-Robot-Kinematics-Simulator
Forward and Inverse Kinematics Simulators for a Synchronous Drive Robot. Includes a slider-controlled forward kinematics simulator and a mouse-click-based inverse kinematics simulator, implemented in Python with Matplotlib for robotics education and research.



This repository provides Forward and Inverse Kinematics simulators for a Synchronous Drive Robot (also known as a synchro drive).  
In this drive system, all wheels steer and rotate together, enabling omnidirectional motion with simplified kinematics.  

This project contains two interactive simulators:

- Forward Kinematics Simulator
  Control the robot’s speed and heading angle using sliders, and visualize the resulting trajectory in real time.  

![image alt](https://github.com/aAfeworki/Synchronous-Drive-Robot-Kinematics-Simulator/blob/main/Forward_Kinematics_Simulator_for_Synchronous_Drive.png?raw=true)

- Inverse Kinematics Simulator
  Select a target point by clicking on the workspace, and the robot computes the required synchronous wheel inputs to reach the goal.  

![image alt](https://github.com/aAfeworki/Synchronous-Drive-Robot-Kinematics-Simulator/blob/main/Inverse_Kinematics_for_Synchronous_Drive_Robot.png?raw=true)

✨ Features

    - 🎚️ Forward Kinematics with interactive sliders  
    - 🖱️ Inverse Kinematics with mouse-click target input  
    - 📈 Real-time trajectory visualization with Matplotlib  
    - 📚 Educational tool for teaching synchronous drive kinematics  
    - 🔧 Simple and extensible for robotics research  




Requirements:

    Python 3.8+

    NumPy

    Matplotlib

    Tkinter (comes pre-installed with most Python distributions)



🚀 Usage

  Forward Kinematics Simulator

Run:
python forward_kinematics.py

Adjust sliders to control linear velocity and heading angle.

Observe the resulting synchronous drive trajectory.


  Inverse Kinematics Simulator

Run:
python inverse_kinematics.py

Click a point in the workspace to set a target position.

The robot calculates synchronous wheel inputs and moves toward the target.




📚 Background

  The Synchronous Drive (synchro drive) robot has all wheels mechanically linked to rotate and steer together.
  Forward Kinematics: Determines the trajectory based on velocity and heading inputs.

  Inverse Kinematics: Computes the control inputs required to reach a target location.

  This project provides an interactive educational platform for exploring synchronous drive principles, widely used in mobile robotics research.

🤝 
Contributions are welcome!
Open issues for bugs or feature requests


Submit pull requests for enhancements



📜 
This project is licensed under the MIT License.

👨‍💻 Author

  Developed by Afework Alemu ✨
If this project helps your learning or research, please consider giving it a ⭐ on GitHub!
