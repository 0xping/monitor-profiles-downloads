# Monitor Profiles downloads

Download the newest release from [Releases](https://github.com/0xping/monitor-profiles-downloads/releases/latest).

- **Windows 10/11:** download MonitorProfiles-windows.zip, extract to a writable folder such as Documents\MonitorProfiles, and run MonitorProfiles.exe. Windows may warn because it has no Authenticode signature.
- **GNOME 50 on Linux:** download MonitorProfiles-linux.zip, extract, and follow README.txt. Requires Python 3.10+, ddcutil, openssl, notify-send and I2C permissions.

Windows checks for updates after startup and every six hours; GNOME checks daily. Updates ask before installation and keep your profiles. Older copies without the updater need the latest package installed once. GNOME needs a logout/login after extension updates.

The app includes Office, Night, Gaming and Movies for MSI MAG 274QF E20 and MSI MP251W E2. The Windows settings window lets you register other DDC/CI monitors and customize profiles.

Downloads are checked against RSA/SHA256-signed release metadata and asset hashes. No GitHub login is needed. The source repository and development history are private; Linux scripts are included because the extension requires them to run.

The Windows build and automated tests run on Windows CI. Physical monitor control and the full Windows update/restart flow still require validation on a Windows PC. DDC/CI must be enabled in the monitor menu; HDR and monitor picture modes can lock some controls.
