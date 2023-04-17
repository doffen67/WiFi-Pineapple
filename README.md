# WiFi-Pineapple

The WiFi Pineapple by Hak5 is a penetration testing tool for wireless network auditing and security. It is based on OpenWRT, a customizable Linux distribution for embedded devices, and utilizes a wireless router capable of running custom firmware. The WiFi Pineapple allows security professionals to monitor, manipulate, and exploit Wi-Fi networks.

Recreating a similar device is possible using a compatible router and open-source software. However, keep in mind that using such devices for unauthorized access or malicious activities is illegal and unethical. The information provided here is for educational purposes only and should be used responsibly and with permission.

To recreate a WiFi Pineapple-like device, follow these steps:

Obtain compatible hardware:
Get a wireless router capable of running custom firmware, such as the GL.iNet GL-AR150, GL-AR300M, or GL-AR750. These routers have similar features to the WiFi Pineapple and can run OpenWRT.

Install OpenWRT on the router:
Visit the OpenWRT website (https://openwrt.org) to download the appropriate firmware for your router model. Follow the installation instructions provided by OpenWRT to flash the firmware onto the router. This process usually involves connecting the router to your computer via an Ethernet cable and using a web interface or command-line tool to flash the firmware.

Configure OpenWRT:
Once the firmware is installed, configure the router's settings (network, Wi-Fi, firewall, etc.) according to your needs. You can access the OpenWRT web interface (LuCI) by connecting to the router's IP address (usually 192.168.1.1) from a web browser.

Install necessary packages:
Install packages that enable wireless network monitoring, manipulation, and exploitation, such as the following:

tcpdump: For capturing network traffic
aircrack-ng: For Wi-Fi network auditing and cracking
mdk4: For wireless network attacks and testing
hostapd: For creating rogue access points
You can install packages using the OpenWRT web interface (LuCI) or by SSHing into the router and using the command-line interface (opkg).

Set up a wireless monitoring and injection interface:
Configure one of the router's wireless interfaces to act as a monitor and packet injection interface, allowing you to capture traffic and perform attacks on nearby Wi-Fi networks.

Develop custom scripts and tools (optional):
You can create custom scripts and tools to automate specific tasks, such as automatically setting up rogue access points, performing man-in-the-middle attacks, or monitoring nearby Wi-Fi networks for vulnerabilities.

Once you have completed these steps, you will have a device capable of performing similar tasks to a WiFi Pineapple. Always use such devices responsibly, ethically, and with proper authorization.
