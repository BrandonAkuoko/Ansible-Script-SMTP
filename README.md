# Ansible-Script-SMTP
In this repository contains an SMTP ansible script using Postfix service
# Usage
Contains 2 files
  - SMTP.yml: Main script that is used
  - Ansible: Zipped directory that contains STMP.yml as well
# Convention
  - ansible folder
  - SMTP.yml: scripted used to deploy Postfix service
# Details
 Each project need its collection of scripts / tasks to do the devops related operations
# Installation Instructions
As a prerequisite for someone who is going to employ this script, you obviously need to have python and ansible installed. Also when you are running the command ansible-playbook smtp.yml you must also include “--ask-become-pass” and then enter the root password [or sudoers password]. This allows you to run root access to install the postfix service.
