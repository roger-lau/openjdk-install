# Installing OpenJDK 8
Follow the instructions below to get started.
Choose your operating system: [Windows](#windows), [Linux](#linux), [Mac](#mac)
<br /><br /><br />

## Windows
1. Install OpenJDK 1.8
   * Download this file: https://download.java.net/openjdk/jdk8u41/ri/openjdk-8u41-b04-windows-i586-14_jan_2020.zip
   * Unzip the downloaded file to folder of your choice, e.g., `C:\`
   * Set the path to `bin\` to `PATH` environment variable, e.g., `C:\java-se-8u41-ri\bin\`
   * Set the path to the installation folder to `JAVA_HOME` environment variable, e.g., `C:\java-se-8u41-ri\`

		###### Note:
	   > If the download link doesn't work anymore, find the download link in https://jdk.java.net/java-se-ri/8-MR3
	  
		###### Check:
		> Type `java -version` in command line. It should return `version "1.8.XXXXX"`

## Linux
1. Install OpenJDK 1.8
	##### Method 1 (Easier)

   * Using apt-get (Ubuntu): `sudo apt-get install openjdk-8-jdk`
   * Using yum (CentOS, Redhat): `sudo yum install java-1.8.0-openjdk-devel`
    
	##### Method 2
   * Download this file: https://download.java.net/openjdk/jdk8u41/ri/openjdk-8u41-b04-linux-x64-14_jan_2020.tar.gz
   * Run `tar xvf openjdk-*.tar.gz` to untar the downloaded file to folder of your choice, e.g., `/opt/`
   * Set the path to `bin/` to `PATH` environment variable, e.g., `/opt/java-se-8u41-ri/bin/`
   * Set the path to the installation folder to `JAVA_HOME` environment variable, e.g., `/opt/java-se-8u41-ri/`
   
   		###### Note:
		> If the download link doesn't work anymore, find the download link in https://jdk.java.net/java-se-ri/8-MR3
	   

		###### Check:
		> Type `java -version` in command line. It should return `version "1.8.XXXXX"`

## Mac
1. Install OpenJDK 1.8
   * Run `brew tap AdoptOpenJDK/openjdk`
   * Run `brew cask install adoptopenjdk8`
   * Run `/usr/libexec/java_home -V` to find the path to your java home for version 1.8
   * Set `JAVA_HOME` to that path

	###### Check:
	> Type `java -version` in command line. It should return `version "1.8.XXXXX"`