# Install-Office365-Apps
Use this PSADT script to install and uninstall your Office 365 apps using a custom .xml file

You can create your .xml configuration file by logging into config.office.com

Detection key used for a specific version or greater than the specific version

You can use other keys under: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\ClickToRun\Configuration



Method: Registry

Key Path:
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\ClickToRun\Configuration

Value Name:

VersionToReport

Detection Method:

Version comparison

Operator:

Greater than or equal to

Value:

16.0.19127.20484

