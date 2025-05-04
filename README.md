# Install Autopsy and Analyze the Disk File and Folder Configuration
# NAME : Selva Jobin S
# REGISTER NUMBER : 212223220102
# AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

# DESIGN STEPS:
# Step 1: Install VirtualBox
🔗
Installation Steps:
1.Download the Windows hosts .exe file from the official VirtualBox website.
2.Run the installer and follow the on-screen instructions.
3.Once installed, launch VirtualBox to verify the installation.

# Step 2: Install Kali Linux on VirtualBox
🔗 Download Kali Linux VM: Click Here

Installation Steps:
1.Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).
2.Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.
3.Go to Settings > Storage, click Empty under Controller: IDE.
4.Select Graphical Install, follow the prompts to set language, location, username, and password.
5.Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.

# Step 3: Install Autopsy (GUI-based Forensic Tool)
🔗 Download Autopsy: Click Here

Installation Steps:
Download the Autopsy Windows Installer from the official website.
Extract the ZIP file and open the bin folder.
Run autopsy.exe and set up a new forensic case for analysis.

# Step 4: Install Sleuth Kit (CLI-based Forensic Tools)
🔗 Download Sleuth Kit: Click Here

Installation Steps:
1.Download the Windows ZIP package from the official website.
2.Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).
3.Add the bin folder to Windows PATH:
4.Open Control Panel → System → Advanced System Settings.
5.Click Environment Variables → Edit Path.
6.Add the Sleuth Kit bin folder path and save changes.
7.Verify installation by running:
```
fls -version
```
# Step 5: Create & Configure a Virtual Hard Disk (VHD) in Windows
1.Press Win + X, Select Disk Management.
2.Click Action > Create VHD.
3.Choose a location and set a disk size (e.g., 10GB+).
4.Select Fixed Size or Dynamically Expanding and click OK.
5.In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select MBR.
6.Right-click Unallocated Space → New Simple Volume → Format the disk -> Click next → Finish.

# OUTPUT:
# Virtual Box:

![image](https://github.com/user-attachments/assets/8e8bccbd-5996-4b63-827f-6923e72e9ddd)


# Virtual Machine (Kali Linux)

![image](https://github.com/user-attachments/assets/2f022d6c-e1b1-4321-a660-754c388dbde8)


Autopsy

![image](https://github.com/user-attachments/assets/9cf96c06-7d51-414f-94fc-647890e101ee)

![image](https://github.com/user-attachments/assets/582e1ba2-ee8b-4186-9e59-3e7691a9fbb1)


# Sleuth Kit

![image](https://github.com/user-attachments/assets/850933da-ae36-4dd4-918e-411c85e50839)

![image](https://github.com/user-attachments/assets/08bf72b4-acc1-4be0-baaa-2d98217b6e66)


#  Creation of Virtual Hard Disk

![image](https://github.com/user-attachments/assets/615db4a5-c45d-46c8-b932-1f68b0de7ff1)

![image](https://github.com/user-attachments/assets/293aef7a-dac2-4c65-b954-f96188007450)


# RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
