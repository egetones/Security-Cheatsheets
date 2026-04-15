# Fedora & DNF Cheatsheet

Useful commands for Fedora Workstation management.

## Package Management (DNF)

| Action | Command |
| :--- | :--- |
| Update System | `sudo dnf update` |
| Install Package | `sudo dnf install <package_name>` |
| Search Package | `sudo dnf search <keyword>` |
| Remove Package | `sudo dnf remove <package_name>` |
| Clean Cache | `sudo dnf clean all` |
| History/Undo | `sudo dnf history undo last` |

## System & Services (Systemd)

```bash
# Start a service
sudo systemctl start httpd

# Enable service on boot
sudo systemctl enable httpd

# Check status
systemctl status httpd

# Analyze boot time
systemd-analyze blame
