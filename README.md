# sTetro: Revolutionizing Staircase-Cleaning Robotics

Overview
The sTetro stands as a pioneering solution, delivering a new era of cleaning automation. Designed with a vertical conveyor belt mechanism, this cutting-edge robot transcends conventional cleaning capabilities by effortlessly navigating across flat surfaces and ascending staircases. Inspired by the Tetris Tiling Theory, the sTetro's innovative concept reshapes traditional cleaning robotics. Its structural foundation comprises three interconnected cuboids, each linked by two sliders affixed to the central cuboid. This intelligent robot dynamically reconfigures itself upon encountering a staircase, showcasing unparalleled motion mechanisms tailored for efficient staircase cleaning.

## Contribution to this Project:
### Motion Controller Development
The heart of the sTetro lies in its intricate staircase motion controller. My pivotal contribution involves crafting a state-of-the-art, state-machine-based controller where each distinct state meticulously analyzes a suite of sensors seamlessly integrated into the robot to make motion-based decisions. Additionally, I designed and integrated an encoder and IMU-based PID controller, ensuring the robot's smooth and adaptive motion while traversing various terrains.

### Computer Vision: (Staircase Detection)
Accurate detection of staircases is paramount for seamless shape-shifting. Leveraging my prior project's success, I applied a Deep CNN to significantly improve the robot's staircase detection capabilities. This involved developing an autonomous stair-climbing algorithm that dynamically modifies the robot's structure and functionality as it ascends stairs. Furthermore, I seamlessly integrated this feature into the robot's cleaning tasks, enhancing its overall functionality. Utilizing the YOLO-v3 Algorithm as a cornerstone, I converted it into a ROS (Robot Operating System) node, enabling seamless integration with the robot's software infrastructure. 

<p align="center">
  <br><br>
  <img src="https://github.com/NigamKatta/sTETRO/blob/main/Assets/sTETRO%20-%20GIF.gif" alt="Project Demo">
  <br><br>
</p>


