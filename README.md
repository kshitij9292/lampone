# Project Name: Handheld Gaming Device & Mini Computer

Welcome to the official GitHub wiki for the Handheld Gaming Device! This project brings retro gaming and modern functionality together in a compact, portable design. Powered by the Banana Pi M2 Zero single-board computer, this device supports retro gaming, serves as a mini-computer running Raspbian, and functions as a smart TV stick.

![](https://github.com/kshitij9292/lampone/blob/main/614fab3c-0d94-46e3-bd91-7222000b7419.PNG?raw=true)

## Introduction
The handheld gaming device allows users to enjoy their favorite retro games from NES, GBC, GBA, NDS, and PS1 platforms. Additionally, it is capable of functioning as a mini-computer and smart TV stick, offering versatility for gaming, productivity, and media streaming.


## Features
- **Multi-platform support**: Play games from NES, GBC, GBA, NDS, and PS1.
- **Mini-computer functionality**: Runs Raspbian OS for productivity tasks.
- **Smart TV stick**: Connects to TVs for media streaming and entertainment.
- **Portable design**: Lightweight and compact, making it easy to carry.
- **Customizable controls**: Includes responsive buttons and D-pad for optimal gaming experience.


## Hardware Specifications
- **Single-board computer**: Banana Pi M2 Zero
- **Display**: 3.5-inch IPS LCD
- **Power**: Rechargeable lithium-ion battery (2000 mAh)
- **Controls**:
  - D-pad and action buttons
  - Start/Select buttons
- **Ports**:
  - Micro USB for charging
  - HDMI output for TV connection
- **Storage**: MicroSD card (up to 128 GB supported)
- **Connectivity**: Wi-Fi and Bluetooth



## Software Setup
### Prerequisites
- A computer with an SD card reader
- A microSD card (16GB or larger)
- Banana Pi M2 Zero
- Raspbian OS image

### Steps
1. **Download Raspbian OS**:
   - Visit the [[official Raspbian download page](https://www.raspberrypi.org/software/)](https://www.raspberrypi.org/software/).
   - Choose the latest image compatible with Banana Pi M2 Zero.

2. **Flash the Image**:
   - Use software like [[Balena Etcher](https://www.balena.io/etcher/)](https://www.balena.io/etcher/) to write the image to the microSD card.

3. **Install Emulator Software**:
   - Set up emulators for NES, GBC, GBA, NDS, and PS1 using RetroPie or other emulator tools.
   - Transfer ROM files to the appropriate directories.

4. **Customize Controls**:
   - Configure button mapping in the emulator settings.

5. **Test the Setup**:
   - Insert the microSD card into the Banana Pi M2 Zero and power up the device.
   - Verify all emulators and buttons function correctly.

---

## Usage Instructions
1. **Gaming Mode**:
   - Power on the device.
   - Navigate to the emulator menu and select the desired platform.
   - Load your favorite game and enjoy!

2. **Mini-computer Mode**:
   - Connect a keyboard and mouse via Bluetooth.
   - Access the Raspbian desktop environment for productivity tasks.

3. **Smart TV Stick Mode**:
   - Use the HDMI output to connect the device to your TV.
   - Stream media or play games on the big screen.



## Troubleshooting
### Common Issues
1. **Device not powering on**:
   - Check the battery level and charge the device if necessary.
   - Ensure the microSD card is properly inserted.

2. **Buttons not responding**:
   - Reconfigure the button mapping in the emulator settings.
   - Inspect hardware connections for loose components.

3. **Emulator not loading games**:
   - Verify the ROM files are in the correct format and directory.
   - Update the emulator software if necessary.





## Contributing
We welcome contributions to improve this project! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description.
