# What this script does
The script configures baseline settings for a Windows device (including optional wifi profile in the Resources folder) and joins it to a local AD domain. It also installs software defined in subfolders that exist in the Software folder.

# What's included
- Resources folder that contains the wifi profile XML file. An example file is included.
- Script folder that contains the PS script file (including a Functions folder that the script depends on).
- Software folder that contains subfolders with installation files and a settings CSV file (to filter installation depending on manufacturer type and to add install arguments). Example subfolders are included.

# How to use
1. Copy all content to a USB drive. Do not change the file/folder structure (except subfolders in the Software folders).
1. Launch "Computer computer.bat" from the freshly install Windows device that should be configured.
1. Follow the script prompts to decide what to install and configure.