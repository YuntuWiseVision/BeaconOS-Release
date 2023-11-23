# BeaconOS-Release

## Introduction
BeaconOS is a Linux kernel-based operating system focused on providing a unified AI model training and inference runtime environment for edge devices and servers. Its open-source architecture and flexible design allow users to customize and extend it to fit their needs. As a brand new operating system, BeaconOS offers an efficient, secure, and stable runtime while providing many advanced features and tools, including an optimized kernel, multi-task manager, virtual desktops, file explorer, and various common applications. Whether for daily use or professional development, BeaconOS is able to provide users with an efficient, enjoyable experience and excellent performance.

## Download
Download the newest BeaconOS IMG from Google Drive
[**Download Here**](https://drive.google.com/drive/folders/1NCHEWVv35h3V81ngbbs9isqSAiF0ivE1?usp=sharing)

## Infrastructure
![架构图](https://github.com/YuntuWiseVision/BeaconOS-Release/assets/148029179/534ee924-7032-4511-89b7-c833513459e0)

## Core Features
1. Compatible with X86 & ARM architectures CPUs, can be deployed on x86 chip-based servers and ARM architecture-based edge devices  

2. Compatible with mainstream AI accelerator devices and chipsets, such as AI accelerator cards and chips from NVIDIA, Intel, Qualcomm, etc., providing hardware support for model deployment

3. Provides both local and cloud-based device management. Local management is suitable for edge computing scenarios, while cloud-based management can centrally manage large-scale devices

4. AI models can be deployed on-demand through a simple graphical interface without any development work required, covering full process from deployment to usage

5. Supports concurrent execution of multiple AI models, with different models able to concurrently leverage underlying compute resources  

6. Compute resource allocation across different AI models can be dynamically adjusted based on actual demand to achieve expected performance

Let me know if you need any clarification or have additional questions!

## Release Note:
### 2023.11
1. New EasyMode version 
1. Front-end rendering of algorithm results
1. Professional mode provides system firewall configuration
1. Docker configuration optimized
1. Shield OS activation related
1. Supports SOPHGO 1684x and 1684 chips

### 2023.10
1. Supports Qualcomm, Innosilicon, RK, Intel x86 Gen12/Gen13 chips
1. Added a new algorithm inference service - ModelFlow
1. Added model repository management
1. More granular algorithm start/stop control logic, unified interaction between Professional Mode and EasyMode
1. Improved front-end and back-end token verification mechanism
1. Logo can be configured
1. Fixed system service memory issues
1. Fixed several EasyMode issues
1. Added waiting state display for EasyMode long operations
1. Added video source addition for EasyMode unlogged-in users
1. Added full screen button in EasyMode
1. Unfriendly error reporting in BeaconOS 3.1.1
1. Globally fixed display of internet connection status
1. Logs for BeaconOS Professional Edition
