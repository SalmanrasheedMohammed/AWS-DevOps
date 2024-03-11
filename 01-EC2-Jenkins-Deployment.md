# AWS-Jenkins

- create a ec2 Instance in AWS
- create a jenkins server with using ubuntu
- open Git bash and copy/paste the IP address to switch on the server
- (ubuntu user) whoami
- (root user) sudo -s
- login into root user
  - sudo apt update
- for jenkins server we need to install java.
  - apt install default-jre
  - java --version
- Jenkins server (download from the Jenkins offical page)
  - sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
  - sudo apt-get update
  - sudo apt-get install jenkins
- To run Jenkins server
  - systemctl status jenkins
- if not (run) server
  - move to ec2 instance and check the security groups and move to inbound rules and allow the port 8080(tcp) allow anywhere
- jenkins server may start running
- cp/paste the <IP address : 8080>

![j1](https://github.com/SalmanrasheedMohammed/AWS-Jenkins/assets/101308889/91faf25e-1095-41ab-ad0d-ffea8e84bdd3)

- copy the above <jenkins path>
- paste into Git bash sever using
  - cat / jenkins path
  - passwd / paste into the jenkins sever
![j2](https://github.com/SalmanrasheedMohammed/AWS-Jenkins/assets/101308889/89c664e3-f4d7-4238-833a-59b74db1a686)
