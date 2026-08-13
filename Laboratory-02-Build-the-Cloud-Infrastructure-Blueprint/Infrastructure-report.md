# Cloud Infrastructure Assessment Report

## 1. Operating System

The KillerCoda environment is running **Ubuntu 24.04.4 LTS (Noble Numbat)**. The operating system information was obtained using the `cat /etc/os-release` command.

## 2. Kernel Version

The Linux kernel version is:

**6.8.0-136-generic**

This information was obtained using the `uname -r` command.

## 3. CPU Model

The CPU model identified in the KillerCoda environment is:

**Intel Xeon E312xx (Sandy Bridge, IBRS update)**

The processor information was obtained using the `lscpu` command.

## 4. Number of CPU Cores

The environment provides:

**1 CPU core / 1 vCPU**

The number of available processing units was identified using the `nproc` command.

## 5. Total RAM

The system has approximately:

**1.9 GiB of RAM**

The `free -h` command showed 1.9 GiB of total memory.

## 6. Disk Capacity

The main root filesystem is:

**/dev/vda1 — 19G**

Approximately **5.4G is used**, while approximately **13G is available**.

The system also has additional filesystems for `/boot` and `/boot/efi`.

## 7. Mounted File Systems

The `df -h` and `findmnt` commands showed several mounted filesystems.

Important mounted filesystems include:

- `/dev/vda1` mounted at `/`
- `/dev/vda16` mounted at `/boot`
- `/dev/vda15` mounted at `/boot/efi`
- `tmpfs` mounted at `/run`
- `tmpfs` mounted at `/dev/shm`
- `tmpfs` mounted at `/run/lock`

The `findmnt` command also displayed system filesystems such as `sysfs`, `proc`, `devtmpfs`, and other Linux virtual filesystems.

## 8. Hostname

The hostname of the KillerCoda server is:

**ubuntu**

This was obtained using the `hostname` command.

## 9. IP Address

The IP address returned by the `hostname -i` command is:

**127.0.0.1**

This is the loopback address reported by the KillerCoda environment.

## Conclusion

The KillerCoda environment provides a small Ubuntu Linux virtual machine that can be used to demonstrate basic cloud infrastructure concepts. It includes one virtual CPU, approximately 1.9 GiB of RAM, a 19G root filesystem, mounted Linux filesystems, and network configuration. These resources work together with the Ubuntu operating system to provide a functional computing environment for running commands and applications.
