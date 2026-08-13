# Cloud Infrastructure Components

## 1. Compute Resources

### Purpose

Compute resources provide the processing power needed to run applications, commands, and services. They mainly include the CPU and memory (RAM) of a computer or cloud server.

### Importance in Cloud Computing

Compute resources are essential because applications require processing power to perform tasks. Cloud computing allows organizations to increase or decrease computing resources based on workload requirements without purchasing additional physical servers.

### KillerCoda Environment

The KillerCoda environment provides **1 vCPU** with an **Intel Xeon E312xx (Sandy Bridge, IBRS update)** processor and approximately **1.9 GiB of RAM**. These resources allow the Linux virtual machine to execute commands and run applications.

---

## 2. Storage Resources

### Purpose

Storage resources provide space for storing the operating system, applications, files, and other data.

### Importance in Cloud Computing

Storage is important because cloud applications need a reliable place to save and retrieve information. Cloud storage also allows organizations to store large amounts of data without depending completely on physical storage devices.

### KillerCoda Environment

The KillerCoda environment has a **19 GiB root filesystem** located at `/dev/vda1`. Approximately **5.4 GiB is used**, while approximately **13 GiB is available**. The environment also contains filesystems mounted at `/boot` and `/boot/efi`.

---

## 3. Networking Resources

### Purpose

Networking resources allow computers, servers, applications, and other devices to communicate and exchange information.

### Importance in Cloud Computing

Networking is important because cloud services need to communicate with users, applications, databases, and other resources. Proper networking also provides connectivity between different components of a cloud environment.

### KillerCoda Environment

The KillerCoda environment reports the hostname as **ubuntu** and the IP address returned by the `hostname -i` command as **127.0.0.1**. This is the loopback address reported by the environment. The networking information demonstrates how a Linux system can identify its hostname and network address.

---

## 4. Operating System

### Purpose

An operating system manages computer hardware and provides the environment required for applications and commands to run.

### Importance in Cloud Computing

The operating system is important because it manages resources such as CPU, memory, storage, and networking. It also provides the tools and environment that cloud engineers use to manage and maintain servers.

### KillerCoda Environment

The KillerCoda environment uses **Ubuntu 24.04.4 LTS (Noble Numbat)** with kernel version **6.8.0-136-generic**. Linux provides the command-line environment used to inspect and manage the virtual machine and its resources.

---

## Relationship Between the Components

The four components work together to create a functional computing environment. The **operating system** manages the available **compute, storage, and networking resources**. Compute resources process applications and commands, storage resources maintain files and system data, and networking resources provide communication capabilities.

In the KillerCoda environment, these components work together inside a virtual machine to provide a basic environment for practicing cloud computing and Linux administration.
