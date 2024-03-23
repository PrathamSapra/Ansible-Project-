# Ansible-Project

**Assignment Outline**
The objective of this assignment is to demonstrate proficiency in applying configuration management and Linux administration tools to deploy a static web server on pre-deployed Linux-based virtual machines. This project focuses on utilizing Ansible for configuration management, adhering to a modularized approach, ensuring compatibility with Debian and RPM-based distributions, and leveraging dynamic inventory in AWS to accommodate the ephemeral nature of cloud environments.

**Project Description**
This project involves creating an Ansible playbook to install a static website on two Ubuntu and two Amazon Linux EC2 instances deployed across multiple availability zones within public subnets. The Ansible playbook relies on dynamic inventory to ensure seamless management of EC2 instances even after re-creation. Termius serves as the Ansible control node, enabling administrators to interact with the dynamic inventory of EC2 instances.

**Instructions for Running the Project**
Ensure Ansible is installed on the Termius host.
Clone this repository to the Termius environment.
Customize the Ansible playbook according to your specific requirements, such as website content, server configurations, etc.
Ensure that dynamic inventory is correctly configured to manage the EC2 instances.
Run the Ansible playbook using the appropriate command.
Verify the deployment by accessing the static website on the deployed EC2 instances.
Repository Structure
playbook.yml: The main Ansible playbook responsible for deploying the static website.
inventory.yml: Dynamic inventory configuration file for managing EC2 instances.
templates/: Directory containing templates for website content or configuration files.
README.md: This file, providing an overview of the project and instructions for running it.
Architecture Diagram
![image](https://github.com/PrathamSapra/Ansible-Project-/assets/137300683/c4d38d61-8d5a-4ae8-a055-f2302cb8d740)
![image](https://github.com/PrathamSapra/Ansible-Project-/assets/137300683/26a16e07-9dae-4cd6-b54f-b779332a6bc9)



**Credits**
This project was completed as a college assignment with guidance from Leo Lu
For further details or inquiries, feel free to contact pssapra@myseneca.ca
