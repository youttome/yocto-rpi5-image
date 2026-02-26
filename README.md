
# Yocto Base Configuration for Raspberry Pi 5

This configuration defines a customized Yocto environment 
optimized for building embedded Linux images targeting 
the Raspberry Pi 5 platform.

It uses the Poky reference distribution with systemd as 
the init manager and includes support for package management,
AI/ML libraries, and essential development tools.

### Key Highlights:
- **Target Machine:** raspberrypi5 (64-bit)
- **Distro:** poky (systemd)
- **Build Optimizations:** parallel make (6 threads)
- **Package Management:** APT, dpkg enabled
- **Network & Utilities:** SSH (Dropbear + OpenSSH), NFS, net-tools
- **System Monitoring Tools:** htop, iotop, iftop, sysstat, procps
- **AI & Vision Support:** OpenCV, TensorFlow Lite, ONNX Runtime, 
  Arm Compute Library, OpenCL ICD loader
- **Python Environment:** Python 3.12+ with NumPy, Pillow, OpenCV bindings
- **Graphics:** Mesa as the preferred libGL provider

This setup is designed for developers working on AI, robotics, 
and vision-based applications on the Raspberry Pi 5 using Yocto.
