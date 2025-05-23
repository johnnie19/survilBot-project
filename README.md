---

# survilBot-project

A robotics lab project integrating TurtleBot control, camera functionalities, and Telegram bot communication.

## 🧠 Project Overview

This project aims to develop a surveillance robot (`survilBot`) that combines:

* **TurtleBot Control**: Autonomous navigation and movement using ROS.
* **Camera Integration**: Real-time image capture and processing.
* **Telegram Bot Communication**: Remote control and monitoring via Telegram.

## 📁 Repository Structure

* `launch/`: ROS launch files to initialize various nodes.
* `scripts/`: Python scripts for robot control and functionalities.
* `turtleBot_photos/`: Captured images from the robot's camera.
* `CMakeLists.txt` & `package.xml`: ROS package configuration files.

## ⚙️ Installation & Setup

1. **Prerequisites**:

   * ROS (Robot Operating System) installed.
   * Python dependencies as specified in your scripts.

2. **Clone the Repository**:

   ```bash
   git clone https://github.com/johnnie19/survilBot-project.git
   cd survilBot-project
   ```

3. **Build the Package**:

   ```bash
   catkin_make
   source devel/setup.bash
   ```

4. **Run the Launch File**:

   ```bash
   roslaunch launch/your_launch_file.launch
   ```

*Replace `your_launch_file.launch` with the appropriate launch file name.*

## 📸 Features

* Autonomous navigation using TurtleBot.
* Real-time image capture and storage.
* Remote control via Telegram bot commands.

## 🔗 Reference Links

* **TurtleBot Control**:

  * [Clearpath Robotics Guide](https://www.clearpathrobotics.com/assets/guides/kinetic/turtlebot/index.html#)
  * [ROS TurtleBot Tutorials](http://wiki.ros.org/turtlebot/Tutorials/indigo)

* **Telegram Bot Integration**:

  * [Creating a Telegram Bot with Raspberry Pi](https://maker.pro/raspberry-pi/projects/how-to-create-a-telegram-bot-with-a-raspberry-pi)

* **Camera Functionality**:

  * [TurtleBot Camera Tutorial](https://learn.turtlebot.com/2015/02/04/3/)
  * [OpenCV Display Image Tutorial](https://docs.opencv.org/4.5.0/db/deb/tutorial_display_image.html)

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
