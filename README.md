USB PHYSCIAL SECURITY



The "USB Physical Security Controller" project addresses the need for enhanced security measures concerning USB port accessibility. This project provides a user-friendly interface through a Tkinter-based application on a Python platform, allowing users to enable or disable USB ports on their system. The application prompts users to enter a predefined password for authorization, ensuring only authorized users can control the USB ports. Upon successful authentication, the application executes commands to enable or disable the USB ports accordingly, enhancing the physical security of the system.


Use Case Scenario:

In environments where USB port access needs to be restricted for security purposes, such as in corporate offices, laboratories, or educational institutions, the "USB Physical Security Controller" proves invaluable. Suppose an administrator or user desires to prevent unauthorized access to USB ports to mitigate the risk of data theft or malware infection. In that case, they can use this application to easily disable USB ports when not in use or when in a secure environment. Conversely, users can enable USB ports when legitimate USB device usage is required, providing a flexible and convenient solution to manage USB port security effectively.

Implementation:

The implementation of the "USB Physical Security Controller" involves a Python-based application utilizing the Tkinter library for the graphical user interface (GUI). The application requires the user to input a predefined password for authentication before executing commands to enable or disable USB ports. Leveraging subprocess module commands, the application interacts with the system's registry to modify USB port settings accordingly. This implementation ensures simplicity, reliability, and effectiveness in controlling USB port access while maintaining system security.

Requirements:

Python interpreter installed on the system
Tkinter library for GUI development
Access to system registry for USB port manipulation
Predefined password for authentication purposes
