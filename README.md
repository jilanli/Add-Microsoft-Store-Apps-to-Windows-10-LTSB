# Add Microsoft Store Apps to Windows 10 LTSB without the Microsoft Store

To install the prerequisites for AppInstaller run the "AppInstaller.ps1" PowerShell script with a user account that has elevated privileges.

To add store Apps you will need to download the required "appxbundle" file. 

For example to install "Photos" app you can either double click on it after installing the prerequisites or run the command below in PowerShell.

  - Add-AppxPackage -Path "*Microsoft.Windows.Photos_2017.35063.44410.0_neutral___8wekyb3d8bbwe.appxbundle"
