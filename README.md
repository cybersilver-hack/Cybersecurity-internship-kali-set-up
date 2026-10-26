# Kali Linux Setup

## Overview
Setting up Kali Linux in VirtualBox for my cybersecurity internship.

## Setup
- Software: VirtualBox
- Kali version: 2026.2
- RAM: 4 GB, 2 processors

## Issues & Fixes
- **Problem:** Leftovers from my old setup conflicted with the new install.
- **Fix:** Removed the old setup completely, then reinstalled.

## Screenshot


![Kali desktop]<img width="1920" height="974" alt="screenshot png" src="https://github.com/user-attachments/assets/b07ef410-9c4c-4f0f-bd90-5c7b6307e0ca" />


## Goal
To revise and improve my cybersecurity skills.

## Network Setup
- Adapter 1: NAT Network
- NAT Network gives Kali internet access and lets multiple VMs on the same network talk to each other, while keeping them isolated from my main home network.
- Used for updating tools with apt and for lab practice between VMs.

## Resources
- [7-Zip](https://www.7-zip.org)
- [VirtualBox](https://www.virtualbox.org)
- [Kali Linux](https://www.kali.org/get-kali/)

  ## Lab Setup Procedure
1. Downloaded the Kali Linux VirtualBox image from kali.org
2. Extracted the downloaded file using 7-Zip
3. Opened VirtualBox and clicked Machine > Add (or double-clicked the .vbox file)
4. Set the VM to 4 GB RAM and 2 processors
5. Set the network adapter to NAT Network
6. Started the VM and logged in
7. Ran `sudo apt update` to update the system
   
## Author
**Silifat Damilola Olanrewaju**

LinkedIn: [My LinkedIn profile](https://www.linkedin.com/in/silifat-olanrewaju/)

## Project Information
Program Name: Cybersecurity at Networkwalks |Week:01 |Project:Cybersecurity & Pentesting Lab Setup |Repository:Github
