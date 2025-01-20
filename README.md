#This repository  marks the beginning of my journey in developing cybersecurity applications and scripts in python.

The purpose of this code, as the name suggests, is to change the MAC (Media Access Control) Address of the network device.
This is a Python code but can also be run as an executable.
User needs to specify the interface as well as the new MAC address in the command.
This is the first time I developed a script that can be used cross-platform in any Linux distro.
It makes use of various Python libraries like SUBPROCESS, OPTPARSE, RE.

This code is well functioning and tested and also provides meaningful errors for better usability.

I got the idea for this code from the course 'Learn Python & Ethical Hacking From Scratch' by Zaid Sabih, zSecurity. 

<br/>
<br/>

<h2>USAGE</h2>

<h4>1. Clone this Repository</h4>

<h4>2. CD to the cloned repository folder/directory</h4>

<h4>3. Run the script with the command 'python mac-changer.py'</h4>

<h4>4. Check the usage and open help with '--help' for more info</h4>

![Capture1](https://github.com/user-attachments/assets/d582d0b9-f62a-417b-96fb-bd97fedc72f9)


<h4>5. Run 'ifconfig' to see network interfaces and their associated MAC addresses</h4>

![Capture2](https://github.com/user-attachments/assets/432e3c62-675c-4116-a877-dda9e6707163)


<h4>6. Run the script with the desired network interface and provide a new MAC address for the network interface with the appropriate usage options (use sudo)</h4>

<h4>7. Run 'ifconfig' to confirm the change in MAC address of the selected network interface</h4>

![Capture3](https://github.com/user-attachments/assets/012e32cd-9e22-4171-b692-5591e443925b)
