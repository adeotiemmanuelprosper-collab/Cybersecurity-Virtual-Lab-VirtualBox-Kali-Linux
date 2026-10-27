# Cybersecurity-Virtual-Lab-VirtualBox-Kali-Linux
     
     Project Overview 


As part of my cybersecurity learning journey with NetworkWalks, I completed my first practical task setting up a virtual cybersecurity lab using Oracle VirtualBox and Kali Linux.

The goal was to create an isolated and controlled environment for learning networking, ethical hacking, vulnerability assessment, and other cybersecurity concepts.

    Objectives


Install and configure Oracle VirtualBox.<img width="1366" height="768" alt="Screenshot 2026-10-27 083038" src="https://github.com/user-attachments/assets/1d7e3087-6e34-452a-bf48-fe1ef51c362e" />


Set up Kali Linux as the attacking and testing machine.

Create a custom NAT Network using the 10.0.0.0/24 subnet.

Configure Kali Linux with the planned static IP address 10.0.0.2/24.

Enable internet connectivity for updates and learning resources.

Configure clipboard and drag-and-drop integration.

Configure a shared host folder for file exchange.

Take a virtual machine snapshot to support recovery.<img width="1366" height="768" alt="Screenshot 2026-10-27 083355" src="https://github.com/user-attachments/assets/ad8aa048-6cef-422d-8695-8cc634e0a6d6" />



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

10.0.0.2/24<img width="1366" height="768" alt="Screenshot 2026-10-27 082423" src="https://github.com/user-attachments/assets/a6bc36a9-5608-4ab0-9ee3-b3a8c4a40efb" />


Shared folder

Host /downloads folder

Recovery method

Virtual machine snapshot

Note: The table describes the intended lab configuration. Confirm the IP address, shared folder, and connectivity on your actual setup before treating each item as verified.

Tools and Technologies

Oracle VirtualBox

Kali Linux<img width="1366" height="768" alt="Screenshot 2026-10-27 083038" src="https://github.com/user-attachments/assets/02b6ce20-ca59-40f9-a1da-7963d0645185" />


Virtual networking and NAT

Linux network configuration

Virtual machine snapshots

Work Completed

Installed the required virtualisation software.

Created the custom NAT Network for the lab.<img width="1366" height="768" alt="Screenshot 2026-10-26 205925" src="https://github.com/user-attachments/assets/cce24f64-6652-4224-9aef-e17fd74856cb" />



Imported and configured the Kali Linux virtual machine.

Worked on the network interface and static IP configuration.

Configured virtual machine integration features.

Prepared the environment for future cybersecurity exercises.

Created a snapshot to make recovery easier after lab changes.<img width="1366" height="768" alt="Screenshot 2026-10-27 082423" src="https://github.com/user-attachments/assets/1946783b-00cb-47c5-94ce-62dff4ddaaa1" />


     Testing and Validation
  

The following checks are useful for confirming the environment is ready:

Verify the Kali IP address with ip addr.

Verify the default route with ip route.<img width="1366" height="768" alt="Screenshot 2026-10-27 082655" src="https://github.com/user-attachments/assets/0b0fe4ee-6cc1-4806-9bcb-47dcfa2f6626" />

Test connectivity to the configured gateway.

Test internet connectivity with ping -c 4 1.1.1.1.<img width="1366" height="768" alt="Screenshot 2026-10-27 082918" src="https://github.com/user-attachments/assets/9c9ffaec-572f-453d-920b-88ff4edbf2f3" />

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
