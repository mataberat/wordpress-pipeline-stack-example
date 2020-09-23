# WordPress CI/CD Pipeline Example

## Introduction
Manage WordPress deployment on traditional Virtual Machine with an automation manner. Empowering the CI/CD pipeline to enhance the workflow.

## Tools
- Ansible
- Jenkins

## Servers Topology

IP CIDR: 192.168.139.0/24
WordPress Servers IP Range: [192.168.139.30 - 192.168.139.40]
MySQL Database IP: 192.168.139.100
Jenkins Server IP: 192.168.139.110

## Setting up the Python Virtual Environment
This repository initiated using Python 3.8.5. It's very recommended to use the same Python version to minimize the unsupported Ansible and their kind of environment. I prefer to use [pyenv](https://github.com/pyenv/pyenv) and [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) to easy switch your Python version.

If `pyenv` and `pyenv-virtualenv` have already installed on the system. Run this command to install Python and create a virtual environment.
```python
$ pyenv install 3.8.5
$ pyenv virtualenv 3.8.5 wordpress-pipeline-stack-example
$ pyenv activate wordpress-pipeline-stack-example
$ pip install -r requirements.txt
```
