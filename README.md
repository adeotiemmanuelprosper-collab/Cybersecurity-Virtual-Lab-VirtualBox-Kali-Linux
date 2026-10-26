# Cybersecurity-Virtual-Lab-VirtualBox-Kali-Linux
Project Overview
As part of my cybersecurity learning journey with NetworkWalks, I completed my first practical task setting up a virtual cybersecurity lab using Oracle VirtualBox and Kali Linux.

The goal was to create an isolated and controlled environment for learning networking, ethical hacking, vulnerability assessment, and other cybersecurity concepts.

Objectives

Install and configure Oracle VirtualBox.

Set up Kali Linux as the attacking and testing machine.

Create a custom NAT Network using the 10.0.0.0/24 subnet.

Configure Kali Linux with the planned static IP address 10.0.0.2/24.

Enable internet connectivity for updates and learning resources.

Configure clipboard and drag-and-drop integration.

Configure a shared host folder for file exchange.

Take a virtual machine snapshot to support recovery.

Lab Architecture

Component

Configuration

Host operating system

Windows

Virtualisation platform

Oracle VirtualBox

Security testing VM

Kali Linux

Network type

Custom NAT Network

Network subnet

10.0.0.0/24

Planned Kali IP

10.0.0.2/24

Shared folder

Host /downloads folder

Recovery method

Virtual machine snapshot

Note: The table describes the intended lab configuration. Confirm the IP address, shared folder, and connectivity on your actual setup before treating each item as verified.

Tools and Technologies

Oracle VirtualBox

Kali Linux

Virtual networking and NAT

Linux network configuration

Virtual machine snapshots

Work Completed

Installed the required virtualisation software.

Created the custom NAT Network for the lab.

Imported and configured the Kali Linux virtual machine.

Worked on the network interface and static IP configuration.

Configured virtual machine integration features.

Prepared the environment for future cybersecurity exercises.

Created a snapshot to make recovery easier after lab changes.

Testing and Validation

The following checks are useful for confirming the environment is ready:

Verify the Kali IP address with ip addr.

Verify the default route with ip route.

Test connectivity to the configured gateway.

Test internet connectivity with ping -c 4 1.1.1.1.

Test DNS resolution with getent hosts www.networkwalks.com.

Confirm the shared folder works as expected.

Confirm that the virtual machine snapshot is available.

Successful ping tests alone do not prove that every network setting is correct. DNS, routing, shared-folder access, and the configured IP should be checked separately.

Security Considerations

Use the lab for authorised cybersecurity learning and testing only.

Keep deliberately vulnerable machines isolated from networks that do not belong to the lab.

Use snapshots before making significant configuration changes.

Never include passwords, session tokens, private keys, or sensitive personal information in screenshots or repository files.

Review network settings before introducing additional virtual machines.

Learning Outcomes

This practical exercise helped me understand the importance of virtualisation, network configuration, IP addressing, NAT networking, and preparing a controlled environment for cybersecurity testing.

It also reinforced that a properly configured lab is an important foundation for learning ethical hacking safely.

Next Steps

Verify connectivity between lab machines.

Add additional lab VMs when required by the training.

Practise network reconnaissance within the authorised lab.

Progress towards vulnerability assessment and penetration testing.

Document each exercise, observation, and lesson learned.

Acknowledgement

This lab setup was completed as part of my cybersecurity learning journey with NetworkWalks.

Thank you to the NetworkWalks team and Waqas Karim (CCIE) for the opportunity to learn and grow.

Project status: Initial lab setup completed; individual configuration and connectivity checks should be documented as verified.
