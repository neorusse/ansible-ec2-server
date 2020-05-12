# AWS EC2 Nginx Server

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Provisioning of AWS EC2 Ngnix Server Instance using Jenkins, Boto, and Ansible.

### Dependencies

##### 1. AWS Account

You would require to have an AWS account to be able to build cloud infrastructure.

##### 2. VS Code Editor

An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download).

### Tools

#### 1. Jenkins

[Jenkins](https://www.jenkins.io/) is a free and open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery. It is a server-based system that runs in servlet containers such as Apache Tomcat.

#### 2. Ansible

[Ansible](https://www.ansible.com/) is an open-source software provisioning, configuration management, and application-deployment tool. It runs on many Unix-like systems, and can configure both Unix-like systems as well as Microsoft Windows.

#### 3. Boto

Boto is a Python package that provides programmatic connectivity to Amazon Web Services (AWS).

To create the AWS Resources, run ansible playbook

```bash
$ ansible-playbook -i inventory mail.yaml
```

### License

[MIT](https://opensource.org/licenses/MIT)

### Author

[Russell Nyorere](https://neorusse.github.io/)
