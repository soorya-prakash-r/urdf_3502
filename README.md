# 🦾 Simple URDF Robot

A minimal URDF project demonstrating a two-link robot arm with revolute joints.  
Designed for learning and visualization in **ROS 2** using **RViz2**.

---

## ⚙️ Features
- Basic URDF robot with 2 links and 2 revolute joints  
- Visualization using **RViz2**  
- Interactive joint control via **Joint State Publisher GUI**  

---

## 🚀 Usage
```bash
cd ~/ros2_ws/src
git clone https://github.com/YourUsername/simple_urdf.git
cd ~/ros2_ws
colcon build
source install/setup.bash
ros2 launch simple_urdf display.launch.py
