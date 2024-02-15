## Jenkins Docker Project
This project demonstrates how to set up Jenkins using Docker. Jenkins is a powerful automation server used for continuous integration and continuous delivery (CI/CD) pipelines.

## Overview

Jenkins is a powerful tool that automates the building, testing, and deployment of software projects. By using Docker, we can easily set up and manage Jenkins instances in isolated containers.

## Table of Contents

- [Background](#background)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Background

Jenkins, coupled with Docker, revolutionizes software development by streamlining Continuous Integration and Continuous Delivery (CI/CD) processes. As an open-source automation server, Jenkins orchestrates tasks like building, testing, and deploying applications. Docker provides lightweight, portable containers for packaging software, ensuring consistent environments across development, testing, and production. Together, Jenkins and Docker empower teams to automate workflows, accelerate development cycles, and enhance collaboration, ultimately delivering high-quality software more efficiently.

## Features

- Easy Setup: Quickly set up Jenkins using Docker without worrying about dependencies.
- Scalability: Dockerized Jenkins instances can be easily scaled up or down based on workload.
- Portability: Docker containers ensure consistency across different environments.
- Customizability: Easily customize Jenkins configurations and plugins to suit your project requirements.
- Automation: Automate build, test, and deployment processes with Jenkins pipelines.

## Prerequisites

Before setting up Jenkins with Docker, make sure you have the following prerequisites:
- Virtualization Software: Install Oracle VM VirtualBox on your machine.
- Operating System Image: Download a Linux CentOS ISO image from the CentOS website.
- Sufficient Resources: Ensure your machine has enough CPU, RAM, and disk space to run the virtualized environment.

Setting up Linux CentOS on Oracle VM VirtualBox
Install Oracle VM VirtualBox:
- Download the Oracle VM VirtualBox installer from the official website.
- Follow the installation instructions for your operating system.

Create a New Virtual Machine:
- Open Oracle VM VirtualBox and click on the "New" button.
- Enter a name for your virtual machine (e.g., "CentOS").
- Choose "Linux" as the type and "Red Hat (64-bit)" as the version.
- Allocate memory based on your system requirements.
- Create a new virtual hard disk with dynamically allocated storage.

Configure Virtual Machine Settings:
- Select the newly created virtual machine and click on "Settings".
- In the "System" tab, adjust the boot order to ensure that the optical drive is first in the list.
- In the "Storage" tab, add the CentOS ISO image as a virtual optical disk.
- Click "OK" to save the settings.

Install CentOS:
- Start the virtual machine.
- CentOS installer should boot from the virtual optical disk.
- Follow the on-screen instructions to install CentOS on the virtual machine.
- Choose appropriate options such as language, keyboard layout, and partitioning.

Complete Installation:
- Once the installation is complete, reboot the virtual machine.
- Log in to CentOS using the credentials you provided during the installation process.

Before installing Docker, ensure that your system meets the following requirements:
- Supported Operating System: Docker supports a wide range of operating systems including Linux, macOS, and Windows. Ensure that your operating system is supported by Docker.
- Hardware Requirements: Verify that your system meets the minimum hardware requirements specified by Docker.
- Internet Connection: Ensure that your system has access to the internet to download Docker packages and dependencies.
- Administrative Privileges: You may need administrative privileges to install Docker on some platforms.

## Istallation

1. Clone this repository: 

   ```bash
   git clone https://github.com/cloudsolutionstech/cst-jenkins-lab.git
   ```

2. Navigate to the repository directory:
  
   ```bash
   cd cst-jenkins-lab
   ```

3. Follow the instructions in the repository or use the [Installation Guide](docs/InstallationGuide.md) to set up the environment.

## Usage

Follow the instructions in this [Usage Guide](docs/UsageGuide.md) README to set up Jenkins using Docker and start automating your CI/CD workflows. Once Jenkins is set up, you can use it to create and manage CI/CD pipelines for your projects. Here are some common tasks:

Create a New Pipeline:
- Click on "New Item" on the Jenkins dashboard.
Enter a name for your pipeline and select "Pipeline", then click "OK".
Configure your pipeline using a Jenkinsfile or by specifying pipeline script directly.

Trigger a Build:
- Whenever you push changes to your repository, Jenkins can automatically trigger a build based on your configured webhook or polling interval.

View Build Results:
- Jenkins provides detailed build logs and reports, allowing you to analyze the outcome of each build.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request. Follow the guideline outlined in the [Contributing Guide](CONTRIBUTING.md)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.   
