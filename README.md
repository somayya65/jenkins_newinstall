yum install wget
sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
yum install java-11-openjdk
yum install fontconfig java-11-openjdk
yum install jenkins
systemctl start jenkins
service jenkins status
systemctl enable jenkins
