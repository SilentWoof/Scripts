# Scripts

This repository contains a collection of useful scripts for system administration and automation tasks across Windows (Batch and PowerShell) and Linux (Shell). Each script is designed to address a specific need, such as configuring network interfaces, managing print spoolers, launching browsers in fullscreen, or setting up hardware and software on Intel NUC devices.

## Script Overview

### Batch Scripts (`bat_scripts/`)

- **nic_configure.bat**  
  Automates the configuration of network interface cards (NICs) on Windows systems. Useful for quickly applying network settings or resetting NIC configurations.

- **print_spooler_restarter.bat**  
  Restarts the Windows Print Spooler service. This can help resolve common printing issues without requiring a full system reboot.

### PowerShell Scripts (`powershell_scripts/`)

*Note: To run a powershell Script without fully disabling the protection use:*
*- powershell -ExecutionPolicy ByPass -File /path/to/file.ps1*
*Use with caution—bypassing security checks could expose your system to malicious code if you’re not 100% sure of the script's source.*


- **open_ms_edge_in_fullscreen.ps1**  
  Launches Microsoft Edge in fullscreen (kiosk) mode. Ideal for kiosk setups or digital signage scenarios.

### Shell Scripts (`shell_scripts/`)

- **debian11_setup_intel_NUC6CAYH.sh**  
  Automates the setup and configuration of an Intel NUC6CAYH running Debian 11. Installs necessary packages and applies recommended system settings.

- **debian12_setup_intel_NUC6CAYH.sh**  
  Similar to the above, but tailored for Debian 12 on the Intel NUC6CAYH.

- **pimoroni_fanshim_installer.sh**  
  Installs and configures the Pimoroni Fan SHIM for compatible Raspberry Pi devices, helping to manage device temperature automatically.

---

Feel free to explore each script’s source for usage instructions and customization