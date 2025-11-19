# Migration
# EX 6: MOVING FILES BETWEEN VIRTUAL MACHINES
# NAME: VEMBARASI.A.R
# REG NO: 212224220120
# Aim:
To move the files between virtual machine. You can move files between virtual machines in several ways: • You can copy files using network utilities as you would between physical computers on your network. To do this between two virtual machine: • Both virtual machines must be configured to allow access to your network. • Any of the networking methods (host-only, bridged and NAT) are appropriate. • With host-only networking, you copy files from the virtual machines to the host and vice-versa, since host-only networking only allows the virtual machines see your host computer. • With bridged networking or NAT enabled, you can copy files across your network between the virtual machines. • You can create a shared drive, either a virtual disk or a raw partition, and mount the drive in each of the virtual machines.

# Procedure:
# How to Enable File sharing in VirtualBox.
# Step 1. Install Guest Additions on the Guest machine. Step 2. Configure File Sharing on VirtualBox.

# Step 1. Install Guest Additions on the Guest machine.

Start the Virtuabox Guest Machine (OS).
From Oracle's VM VirtualBox main menu, select Devices > Install Guest Additions *
a. Open Windows Explorer b. Double click at the "CD Drive (X:) VirtualBox Guest additions" to explore its contents.

<img width="741" height="552" alt="image" src="https://github.com/user-attachments/assets/53812be6-7f4f-4200-9f17-01fee35951f7" />


C.Right click at "VBoxWindowsAdditions" application and from the pop-up menu, choose "Run as administrator".

<img width="751" height="346" alt="image" src="https://github.com/user-attachments/assets/598c3421-a269-4d8f-97a3-01928c479966" />


3.Press Next and then follow the on screen instructions to complete the Guest Additions installation.
<img width="759" height="494" alt="image" src="https://github.com/user-attachments/assets/a42f3a87-a55c-40aa-9e4c-9c790abec47a" />


4.When the setup is completed, choose Finish and restart the Virtuabox guest machine. Step 2. Setup File Sharing on VirtualBox Guest Machine.
5.From VirtualBox menu click Devices and choose Shared Folders -> Shared Folder Settings.
<img width="753" height="413" alt="image" src="https://github.com/user-attachments/assets/c8067338-8767-46b0-b588-262841e5ee08" />


2.Click the Add new shared folder icon.
<img width="770" height="441" alt="image" src="https://github.com/user-attachments/assets/bed48ea6-38b0-4a58-9494-39e546d2a0c9" />


3.Click the drop-down arrow and select Other.
<img width="759" height="524" alt="image" src="https://github.com/user-attachments/assets/c3a8f4e1-b661-40f0-b741-9c499aa039e3" />


3.Locate and highlight (from the Host OS) the folder that you want to share between the VirtualBox Guest machine and the Host and click Select Folder. *
Note: To make your life easier, create a new folder for the file sharing, on the Host OS and give it with a recognizable name. (e.g. "Public")
<img width="769" height="398" alt="image" src="https://github.com/user-attachments/assets/72b9411a-6545-48a0-8963-a729c4151c96" />


4.Now, in the 'Add Share' options, type a name (if you want) at the 'Folder Name box, click the Auto Mount and the Make Permanent checkboxes and click OK twice to close the Shared Folder Settings.
<img width="772" height="374" alt="image" src="https://github.com/user-attachments/assets/b72f8130-7d43-488b-8232-f73c442685c6" />


5.You 're done! To access the shared folder from the Guest OS, open Windows Explorer and under the 'Network locations' you should see a new network drive that corresponds to the shared folder on the Host OS.
# Result:
Thus the virtual machine files are moved to another VM.
