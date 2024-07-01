## Nvidia Fan Control

This is the easiest way to control GPU fans. Set and forget.

### Install

```bash
sudo chmod +x install_nvidia_fan_control.sh

sh install_nvidia_fan_control.sh
```

### Check if its running:

```bash
sudo systemctl status nvidia_fan_control.service
```

### Tested with:

|OS|GPU|
|-:|-:|
|Fedora 40 Workstation|Nvidia RTX 3060 12GB|
|Nobara 39|Nvidia RTX 3060 12GB|
