# Version Control - Git
****************************

> _[Git](https://en.wikipedia.org/wiki/Git) is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-
linear workflows._
- Directories
  - [Git basics](git-basic-commands.md)
  - [Git advanced](git-advanced-commands.md)
  
  Resource for practice (https://try.github.io/)


  ##Jenkins Installation Steps

sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
amazon-linux-extras install java-openjdk17 -y
yum install jenkins -y
systemctl restart jenkins
