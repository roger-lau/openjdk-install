# Installing OpenJDK 8 in Linux
##### Method 1 (Easier)

1. Using apt-get (Ubuntu): `sudo apt-get install openjdk-8-jdk`
1. Using yum (CentOS, Redhat): `sudo yum install java-1.8.0-openjdk-devel`
    
##### Method 2
1. Download this file: https://download.java.net/openjdk/jdk8u41/ri/openjdk-8u41-b04-linux-x64-14_jan_2020.tar.gz
1. Run `tar xvf openjdk-*.tar.gz` to untar the downloaded file to folder of your choice, e.g., `/opt/`
1. Set the path to `bin/` to `PATH` environment variable, e.g., `/opt/java-se-8u41-ri/bin/`
1. Set the path to the installation folder to `JAVA_HOME` environment variable, e.g., `/opt/java-se-8u41-ri/`
   
	###### Note:
	> If the download link doesn't work anymore, find the download link in https://jdk.java.net/java-se-ri/8-MR3
		   
	
	###### Check:
	> Type `java -version` in command line. It should return `version "1.8.XXXXX"`
