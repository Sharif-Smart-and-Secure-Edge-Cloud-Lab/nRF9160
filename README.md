# nRF9160 Developer Kit

nRF9160 is a fully integrated SiP (system-in-package) that makes low power LTE technology easy to use. It contains an Arm Cortex-A53 application processor, full LTE modem, and RF front end. RF frontend is used to convert baseband signals to boradband, radio-signals that can be transmitted.1 MB flash memory and 256 KB of RAM is available for application developeing. Arm TrustZone can be used to isolate and protect secure zones of firmware from normal zones. It can help building secure IoT applications that feature secure boot. Protection of authenticated mechanisms, cryptography, payment etc. are some typical examples of Arm TrustZone technology. 

Plus Arm cryptocell enhances security measures further by offering cryptographic and security resources to help protecting your IoT application from attacks. The CryptoCell is specifically designed for low power systems.

## nRF connect SDK
From [documentation](http://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/index.html):
> The SDK contains optimized cellular IoT (LTE-M and NB-IoT), Bluetooth® Low Energy, Thread, Zigbee, and Bluetooth mesh stacks, a range of applications, samples, and reference implementations, as well as a full suite of drivers for Nordic Semiconductor’s devices.

There are 3 ways to install the SDK:

1. Using nRF connect for desktop: It installs everything you need automatically and is a cross-platform tool
2. Installing manually: Just install toolchain and compile the source code. 
3. Installing nRF connect SDK for VS Code: There is a VS code extension that installs everything you need. This is the recommended way.
