# F5 AUTOMATION ANSIBLE USE CASES

## Overview
The Use Cases for the F5 Automation Provisioner to Test Common Secnarios. This is built by F5 Business Development organization.

New Use Cases will be Added Periodically to Provide Additional Senarios for BIG-IP Modules.

## Prerequisites
F5 Automation Provisioner Instance (Deployed)

## Goal
With F5 Automation provisioner and these Scenario Use Cases, users can/will be able to  
- Test Common Deployment Scenarios through Automation with Ansible.
- Fork instances of code to develop their own plugins and automation playbooks.
- Provide feedback on existing and new use cases that are relevant to everyday work
(More features will be added soon)

## How to use?
Follow [F5 Ansible AWS Provisioner](https://github.com/f5alliances/f5_provisioner) for detailed steps to spin up and tear down the sandbox infrastructure using provisioner

1. Login to the Ansible Host (**studentX-ansible**) provided by the F5 Ansible AWS Provisioner

   Use the Workbench information that is stored in a local directory named after the workshop    
   (e.g.TESTWORKSHOP1/instructor_inventory.txt).  
   
   Example:
   
   ```handlebars
   [all:vars]
   ansible_port=22

   [student1]
   student1-ansible ansible_host=34.219.251.xxx ansible_user=centos
   student1-f5 ansible_host=52.39.228.xxx ansible_user=admin
   student1-host1 ansible_host=52.43.153.xxx ansible_user=centos
   student1-host2 ansible_host=34.215.176.xxx ansible_user=centos
   ```

2. Download the f5_ansible_use_cases Repo on the Ansible host

   ```
   cd ~/
   git clone https://github.com/f5alliances/f5_ansible_use_cases.git
   ```
   
   <kbd>
    <img src="images/Github-960.gif">
   </kbd>   

   <br/>
  
3. Launch a Playbook via the use cases.

## Support
This project is a community effort to promote Network and Security automation and is maintained by F5 Business Development (BD). For any feature requests or issues, feel free to open an [issue](https://github.com/f5alliances/f5_ansible_use_cases/issues) and we will give our best effort to address it.
