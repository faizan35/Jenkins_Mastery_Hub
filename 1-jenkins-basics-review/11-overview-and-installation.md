# 1.1 Overview and Installation

## Overview

Jenkins is a powerful automation server that simplifies building, testing, and deploying projects. Before we get started, let's have a brief overview of what Jenkins is and its key features.

### Key Features:

- Continuous Integration and Continuous Deployment (CI/CD)
- Extensive plugin support
- Distributed builds
- Easy configuration through a web interface

## Installation

To install Jenkins, follow these steps:

1. Open [Official Documentation](https://www.jenkins.io/doc/book/installing/) of jenkins.

2. Choose your platform. For this tutorial we choose Linux -> Debian/Ubuntu.
3. Jenkins requires Java to run, install [java](https://www.jenkins.io/doc/book/installing/linux/#installation-of-java).
4. Insatll [Jenkins](https://www.jenkins.io/doc/book/installing/linux/#long-term-support-release).
5. Verify jenkins

- Check version -> `jenkins --version`.
- Check srevice status -> `systemctl status jenkins`.

Installation Completed.

## Useful Commands

1.  Start the Jenkins service (if not started):

```bash
sudo systemctl start jenkins
```

2. Enable Jenkins to start on boot:

```bash
sudo systemctl enable jenkins
```

3. Access Jenkins in your browser by navigating to [http://localhost:8080](http://localhost:8080)

You will be prompted to enter the initial admin password, which can be found by running:

```bash
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
```

Follow the on-screen instructions to complete the installation.

Now you have Jenkins installed and ready to use!
