# sTetro: Revolutionizing Staircase-Cleaning Robotics

Overview
The sTetro stands as a pioneering solution, delivering a new era of cleaning automation. Designed with a vertical conveyor belt mechanism, this cutting-edge robot transcends conventional cleaning capabilities by effortlessly navigating across flat surfaces and ascending staircases. Inspired by the Tetris Tiling Theory, the sTetro's innovative concept reshapes traditional cleaning robotics. Its structural foundation comprises three interconnected cuboids, each linked by two sliders affixed to the central cuboid. This intelligent robot dynamically reconfigures itself upon encountering a staircase, showcasing unparalleled motion mechanisms tailored for efficient staircase cleaning.

Contribution to this Project:
Contributions to the Project
Controller Development
The heart of the sTetro lies in its intricate staircase motion controller. My pivotal contribution involves crafting a state-of-the-art, state-machine-based controller. Each distinct state meticulously analyzes a suite of sensors seamlessly integrated into the robot. The paramount motion execution is orchestrated by a PID controller, leveraging the Depth camera and IMU sensor data to discern the robot's precise orientation and trajectory.

Computer Vision
Accurate detection of staircases is paramount for seamless shape-shifting. Leveraging the advanced capabilities of the YOLO-v3 Algorithm, I engineered a robust solution for detecting staircases. This involved converting YOLO-v3 into a ROS (Robot Operating System) node, ensuring seamless integration into the robot's software infrastructure. Establishing a pipeline between the robot's camera and the YOLO node-enabled swift staircase identification. Upon detection, the state machine seamlessly transitions, triggering the robot's adaptive reconfiguration process.

![Project Demo](https://github.com/NigamKatta/sTETRO/blob/main/Assets/sTETRO%20-%20GIF.gif)
