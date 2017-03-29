## IP Name ##

**Auto-undeploy Workspace Service** is a simple service that allows the VeriStand gateway to undeploy the current Definition File when a user closes the workspace window.

### LabVIEW Version ###

LabVIEW 2016 & Later


### Quality, Limitations ###

The provided code is as is. It has not been extensively tested and requires validation before implementing it in a real-world use case.

### Installation Guide ###

Open the LabVIEW project, and build the source distribution. That will create a <Builds> directory next to the project. You may copy the content of this folder next to your VeriStand project
Open your VeriStand project.
Right-Click on the **Services** item, and select Configure.
Press New. Search for the Auto Undeploy Workspace Service.vi VI that was built in the <Builds> folder. Press OK twice.

Run your VeriStand project. If a user proceeds to a click to close the workspace window, the definition file should undeploy in the next seconds.
Follow the steps above for every VeriStand project you would like to apply this "Undeploy-on-Workspace-Close" feature.

### Dependencies ###

Describe any dependencies of the IP

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*