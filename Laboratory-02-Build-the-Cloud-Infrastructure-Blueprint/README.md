# Mission 2 – Build the Cloud Infrastructure Blueprint

## Mission Overview

This laboratory activity focuses on understanding the basic components of cloud infrastructure and how they work together. A Linux virtual machine was examined using the KillerCoda Playground, and the collected information was documented in Markdown files and stored in GitHub.

## Objectives

The objectives of this laboratory activity are to:
- Investigate the infrastructure of a Linux virtual machine.
- Identify compute, storage, networking, and operating system resources.
- Use Linux commands to collect system information.
- Understand the role of infrastructure components in cloud computing.
- Compare infrastructure services offered by AWS, Microsoft Azure, and Google Cloud Platform.
- Create technical documentation using Markdown.
- Organize and maintain laboratory work using GitHub.

## Cloud Infrastructure Components

The main infrastructure components examined in this laboratory are:

1. **Compute Resources** – CPU and memory used to process applications and commands.
2. **Storage Resources** – Disk space used to store the operating system, applications, files, and data.
3. **Networking Resources** – Network interfaces and IP addresses used for communication.
4. **Operating System** – Linux, which manages system resources and provides the environment for applications and commands.

More details can be found in [cloud-components.md](cloud-components.md).

## Tools Used

- KillerCoda Playground
- Linux terminal
- GitHub
- Markdown
- Web browser

## Linux Commands Executed

The following commands were used to investigate the Linux environment:

```bash
cat /etc/os-release
uname -r
lscpu | grep "Model name"
nproc
free -h
df -h
findmnt
hostname
hostname -I
