# Add Microsoft Store Apps to Windows 10 LTSB without the Microsoft Store

To install the prerequisites for AppInstaller Right click on the "AppInstaller.ps1" PowerShell script, then click on "Run with PowerShell". 

To add store Apps you will need to download the required "appxbundle" file. 

For example to install "Photos" app you can either double click on the "appxbundle" file after installing the prerequisites, or run the command below in PowerShell replacing Microsoft.Windows.Photos.appxbundle with the correct file name. 

  - Add-AppxPackage -Path "*Microsoft.Windows.Photos.appxbundle"
