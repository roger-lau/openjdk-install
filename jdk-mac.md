# Installing OpenJDK 8 in Mac
1. Run `brew tap AdoptOpenJDK/openjdk`
1. Run `brew cask install adoptopenjdk8`
1. Run `/usr/libexec/java_home -V` to find the path to your java home for version 1.8
1. Set `JAVA_HOME` to that path

	###### Check:
	> Type `java -version` in command line. It should return `version "1.8.XXXXX"`