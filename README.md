# Jenkins-installation-in-ubunu and redhat
Jenkins installation in ubuntu



sudo apt update
sudo apt install openjdk-11-jre
java -version
apt-get install maven
mvn --version

 curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
    /usr/share/keyrings/jenkins-keyring.asc > /dev/null
  
   echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
    https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
    /etc/apt/sources.list.d/jenkins.list > /dev/null
	
	sudo apt-get update
	 
	sudo apt-get install jenkins
	
	service jenkins status
	sudo apt install tomcat9 -y
	service tomcat9 status


   sudo yum install java-1.8.0-openjdk-devel
 1  java -version
    2  mvn --version
    3   sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
    4  wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
    5  yum install wget
    6   sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
    7  sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
    8   yum install fontconfig java-11-openjdk
    9   yum install jenkins
   10  service jenkins status
   11  service jenkins restart
   12  systemctl  jenkins restart
   13  systemctl restart jenkins
   14  systemctl start jenkins
   15  systemctl jenkins status
   16  systemctl status jenkins
   17  systemctl restart  jenkins
   18  cd /var/lib/jenkins/secret/
   19  ls -leth
   20  ls -lrth
   21  yum install jenkins
   22  cat /var/lib/jenkins/secrets/initialAdminPassword
   23  yum instal maven
   24  mvn --version
   25  mvn -version
   26  yum install maven
   yum install tomcat -y
   systemctl  status tomcat
   systemctl  start tomcat
   systemctl  status tomcat

