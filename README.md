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
Step 1: Installed VirtualBox

Downloaded and installed Oracle VirtualBox on host machine.

Verified successful installation by launching the VirtualBox Manager.


Step 2: Created Virtual Machines

Created a Windows Virtual Machine using a Windows ISO.

Created an Ubuntu Linux Virtual Machine using an Ubuntu ISO.

Allocated appropriate RAM (2gb for each since I have 8gb total RAM) and storage for each VM.


Step 3: Configured NAT Network

Created a NAT Network in VirtualBox settings.

Attached both Windows and Ubuntu VMs to the same NAT Network.

This allowed both machines to communicate internally while remaining isolated from the host and internet.


Step 4: Verified Network Connectivity

Started both virtual machines.

Checked IP addresses on both systems.

Successfully tested connectivity between Windows and Ubuntu using ping commands
