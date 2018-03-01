# Ansible Role: Visual Studio Code
[![Build Status](https://travis-ci.org/brentwg/ansible-role-visual-studio-code.svg?branch=master)](https://travis-ci.org/brentwg/ansible-role-visual-studio-code)

Ansible role that installs the Microsoft Visual Studio Code editor on Linux.  

## Requirements  

None.  

## Role Variables  

User modifiable variables and defaults are listed below. (For all variables, see `defaults/main.yml`):  
```
code_package_name: "code"
```  
The name of Visual Studio Code application package. (You know, in case it ever changes...)  

## Dependencies

None.

## Sample Playbook

```
- hosts: all
  
  roles:
    - brentwg.visual-studio-code
```  

