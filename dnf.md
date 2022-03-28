# DNF comparison between apt

[page]("https://www.fosslinux.com/47693/fedora-package-management-with-dnf.htm")

| APT commands | DNF commands |
| --- | --- |
| apt update apt-get update | dnf check-update |
| apt upgrade apt-get upgrade | dnf upgrade |
| apt full-upgrade apt-get dist-upgrade | dnf distro-sync or dnf system-upgrade |
| apt remove apt-get remove | dnf remove |
| apt purge apt-get purge | - | 
| apt autoremove apt-get autoremove | dnf autoremove |
| apt search apt-cache search | dnf search |