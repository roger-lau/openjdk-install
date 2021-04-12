# Installing OpenJDK 8 in Windows

1. Download this file: https://download.java.net/openjdk/jdk8u41/ri/openjdk-8u41-b04-windows-i586-14_jan_2020.zip
2. Unzip the downloaded file to folder of your choice, e.g., `C:\`
3. Set the path to `bin\` to `PATH` environment variable, e.g., `C:\java-se-8u41-ri\bin\`
4. Set the path to the installation folder to `JAVA_HOME` environment variable, e.g., `C:\java-se-8u41-ri\`

	###### Note:
	> If the download link doesn't work anymore, find the download link in https://jdk.java.net/java-se-ri/8-MR3
		  
	###### Check:
	> Type `java -version` in command line. It should return `version "1.8.XXXXX"`