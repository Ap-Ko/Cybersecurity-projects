# Cybersecurity-projects
Home Lab-Networking

## OBJECTIVE:
The objective of this project was to build a basic cybersecurity home lab using VirtualBox, which allowed multiple OS (Windows and Ubuntu) to communicate securely within an isolated network. This lab simulates and enterprise like environment used for learning networking and security fundamentals.

## Tools and Technologies Used:
Oracle VirtualBox

Windows VM

Ubuntu VM

NAT Network(VB)

## Lab Architecture

Host Machine (Physical Laptop)

VirtualBox as hypervisor

Two Virtual Machines:

Windows VM

Ubuntu VM

Both VMs connected using a NAT Network to allow internal communication while remaining isolated from the external network.

## Step-by-Step Implementation

STEP 1: Installed VirtualBox

Downloaded and installed Oracle VirtualBox on host machine.

Verified successful installation by launching the VirtualBox Manager.

STEP 2: Created Virtual Machines

Created a Windows Virtual Machine using a Windows ISO.

Created an Ubuntu Linux Virtual Machine using an Ubuntu ISO.

Allocated appropriate RAM (2gb for each since I have 8gb total RAM) and storage for each VM.


STEP 3: Configured NAT Network

Created a NAT Network in VirtualBox settings.

Attached both Windows and Ubuntu VMs to the same NAT Network.

This allowed both machines to communicate internally while remaining isolated from the host and internet.

STEP 4: Verified Network Connectivity

Started both virtual machines.

Checked IP addresses on both systems.

Successfully tested connectivity between Windows and Ubuntu using ping commands

## SCREENSHOT

## Both VMs (Windows and Ubuntu) Running On VirtualBox
![image alt](https://github.com/Ap-Ko/Cybersecurity-projects/blob/45821e47ac7b0c4eb8aee856fa176115e07923d9/Both%20VM%20running.png)

## Windows and Ubuntu NAT configured in VirtualBox for communication:
![image alt](https://github.com/Ap-Ko/Cybersecurity-projects/blob/e12b2441c57f9dd03759e4253d73d0ac3290c789/Windows%20VM-%20NAT.png)

![image alt](https://github.com/Ap-Ko/Cybersecurity-projects/blob/e12b2441c57f9dd03759e4253d73d0ac3290c789/Ubuntu%20VM-NAT.png)

## Ping Successfull:
![image alt](https://github.com/Ap-Ko/Cybersecurity-projects/blob/e12b2441c57f9dd03759e4253d73d0ac3290c789/ping%20successfull.png)
