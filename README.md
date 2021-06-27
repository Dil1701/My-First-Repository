# My-First-Repository
Project from week 13 cybersecurity BC Elk Server

![image](https://user-images.githubusercontent.com/86344327/123557782-be486f00-d747-11eb-95ad-f3fa02c82a30.png)

These files have been tested and used to generate a live ELK deployment on Azure. They can be used to either recreate the entire deployment pictured above. Alternatively, select portions of the Ansible/Full_install.yml.txt file may be used to install only certain pieces of it, such as Filebeat.

Full Install Playbook

This document contains the following details:

Description of the Topologu
Access Policies
ELK Configuration
Beats in Use
Machines Being Monitored
How to Use the Ansible Build
Description of the Topology
The main purpose of this network is to expose a load-balanced and monitored instance of DVWA, the D*mn Vulnerable Web Application.

Load balancing ensures that the application will be highly stable, in addition to restricting access to the network.

Integrating an ELK server allows users to easily monitor the vulnerable VMs for changes to the log files and system metrics.

The configuration details of each machine may be found below.

| Name               | Function       | IP Address | OS |
|--------------------|----------------|------------|------------------|
| JumpBoxProvisioner | Gateway        | 10.0.0.4   | Linux            |
| Web-1              | DVWA Container | 10.0.0.5   | Linux            |
| Web-2              | DVWA Container | 10.0.0.6   | Linux            |
| ELK-Server         | ELK Server     | 10.1.0.4   | Linux            |
