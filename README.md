#### Email: [j.kapukotuwa@research.ait.ie](mailto:j.kapukotuwa@research.ait.ie)
#### LinkedIn: [https://lk.linkedin.com/in/kapukotuwa](https://lk.linkedin.com/in/kapukotuwa)
#### Technical Skills: ROS, Python, PyTorch, TensorFlow, C, PLC, MATLAB, VHDL, Verilog

## Education
- PhD in Computer Engineering | Technological University of the Shannon, IE
- M.Sc. in Electrical and Electronic Engineering | University of Nottingham, UK
- B.Eng.(Hons) in Electronic Engineering | Sheffield Hallam University, UK

## Work Experience
**Associate Lecturer @ Technological University of the Shannon, IE · Part-time (_Jan 2022 - Present_)**
- Master's level project supervision in the area of robotics, machine learning, and computer vision
- Industrial placement supervision for Master's and Bachelor's students
- Undergraduate project supervision in the area of robotics, machine learning, and software development

**Visiting Lecturer @ Study World Lanka Campus, LK  (_April 2019 - October 2019_)**
- Lectured on the following modules: Automation, Robotics and Programmable Logic Controllers (PLCs)

**Senior Electronics Engineer @ Biovest Healthcare Private Limited, LK (_October 2015 - October 2019_)**
- Maintenance, research and development of new medical devices.
- Develop IT and automated products/services for external organizations.

## Projects
### UniROS: ROS-Based Reinforcement Learning Across Simulated and Real-world Robotics

**Publication:** Under Review  
[GitHub](https://github.com/ncbdrck/UniROS)

I created a comprehensive framework for reinforcement learning in robotics, which allows users to train their robots in both simulated and real-world environments concurrently. It simplifies the process of creating reinforcement learning environments for robots and provides a unified interface for training and evaluating the robots in both simulated and real-world environments.

The following diagram illustrates the interconnected components of the proposed system, highlighting the dual-package approach with RealROS for real-world robotic applications and MultiROS for simulated environments. The UniROS layer acts as an abstraction to standardise the communication process, facilitating the creation and management of multiple environment instances. The diagram encapsulates the ROS-based data flow and the primary interfaces for robot control, which handles real-time interactions

![UniROS](/assets/img/abstraction_layers.png)

The following Diagram of a real-time environment implementation strategy for RL with ROS integration, detailing the interaction between the RL Agent process and the RL Environment process. The agent process updates actions based on observations and refines its policy, while the environment-loop thread of the Environment process handles observation creation, reward calculation, and sending actuator commands, all in real-time. This design minimises latency and allows for dynamic interaction between the RL agent and the environment for both simulation and real-world learning tasks.

![Real-time Environment](/assets/img/Ijrr_real_time.png)



### MultiROS: ROS-Based Robot Simulation Environment for Concurrent Deep Reinforcement Learning
[Publication](https://ieeexplore.ieee.org/document/9926475)  
[GitHub](https://github.com/ncbdrck/multiros)

MultiROS is an open-source Robot Operating System (ROS)-based simulation environment designed for concurrent deep reinforcement learning. It provides a flexible and scalable framework for training and evaluating reinforcement learning agents for complex robotic tasks. The simulation environment is based on Gazebo, providing a realistic simulation platform for testing and developing reinforcement learning algorithms.

The following diagram illustrates the MultiROS architecture

![MultiROS](/assets/img/multiros.png)


## Publications
1. J. Kapukotuwa, B. Lee, D. Devine and Y. Qiao, "MultiROS: ROS-Based Robot Simulation Environment for Concurrent Deep Reinforcement Learning," 2022 IEEE 18th International Conference on Automation Science and Engineering (CASE), Mexico City, Mexico, 2022, pp. 1098-1103, doi: 10.1109/CASE49997.2022.9926475. keywords: {Training;Solid modeling;Three-dimensional displays;Service robots;Operating systems;Transfer learning;Reinforcement learning},

